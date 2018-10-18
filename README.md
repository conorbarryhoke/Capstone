# Capstone

## Problem Statement

1. How do people engage with music on YouTube?
2. How can an artist or company describe their music to maximize potential views?

## Required packages:
### Extract, Transform, Load
* pip install --upgrade google-api-python-client
* pip install --upgrade oauth2client
* pip install google_auth_oauthlib
* requests
* json

### Exploratory Data Analysis
* textblob
* wordcloud
### Feature Engineering
* nltk
* re (regex)
### Modeling
* sklearn


Google Project name: "argon-gear-217322"

## Folder guide
Current working notebook: ETL_Alphabet_DataPull
Current working data source: ./data/clean_data_nocomments_noviews_02.10.18

## Data Strategy
I have collected about 8500 unique records by finding everything with the Music category tag, using relevancy only.

At present, I think this will be enough to get started on analysis. There are two remaining priorities right now:
1. Use the YouTube Analytics API to pull in view counts by dates
 * I can batch by weeks for each video, then collect basic stats (mean, med, mode, std. etc.) so that the data can be aggregate
2. Collect comments around peak view dates
* This will ensure comments are relevant (i.e. not Who else remembers this???)
3. View trap around 1000 that lasts till ~50,000. Search algorithm feature?

#Outsanding questions:
* Can we identify a limit that max engagement approaches


#Analysis and Modeling
1. I expect the predictive component to revolve mainly around the following items:
* what time of year the video is released
* duration of the video
* Key words in the title and tags
* Featuring artist, if any
2. I expect the descriptive component to be structured in the following way:
* What things do people talk about on videos they like (topic assessment)
* What is the level of engagement (ratio of likes / views etc.)
* Broad commentary, such as time between major hits

#Results:
##descriptive
* dislike same as comment rate
* pitbull affect = 2.7
##predictive


## Attribution & Reference
1. YouTube data pull structure:   #https://towardsdatascience.com/tutorial-using-youtubes-annoying-data-api-in-python-part-1-9618beb0e7ea
2. Very good breakout of how to structure query strings - user Sefo Noaman:
#https://stackoverflow.com/questions/48253741/youtube-api-v3-and-python-to-generate-list-of-views-likes-on-own-youtube-videos/52484656#52484656
3. Generic YouTube search - Sune Thorsen:
#https://www.quora.com/Is-there-a-way-to-sort-all-YouTube-videos-by-its-view-count
4. YouTube sample requests from publisher:
#https://github.com/youtube/api-samples/blob/master/python/search.py
5. YouTube Data API overview and Reference:
#https://developers.google.com/youtube/v3/docs/
