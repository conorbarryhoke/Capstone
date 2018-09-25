# Capstone

## Problem Statement
The goal of this capstone is to identify charactersitics of high view count music videos on YouTube.
2 Part Problem statement:
1. How can a music production company design songs and release dates to maximize views
2. How can an advertising agency identify which songs are worth 'investing' in - if a potential hit can be identified early, they can be pro-active about ad buys

Required packages:
* pip install --upgrade google-api-python-client
* pip install --upgrade oauth2client
* pip install google_auth_oauthlib

Google Project name: "argon-gear-217322"

## Folder guide
Current working notebook: API_Exploration
Current main data source: ./data/running_data_pull

## Data Strategy
I'd like to hit a dataframe row count of 10,000, with a minimum of 2k to support nlk processing. Additionally, I'm looking at expanding features by incorporating google trends results and topic analysis so this would require some more data points. To maintain a good feature / observation ratio.   

Ultimately, I'm going to be aiming for regression-based analysis to project view count.

There are two possible paths:  
1. Stick with videos only, (see below for expansion)
2. Expand scope to all videos and redefine the problem. Are there features of charlie bit my finger that can be quantified? Maybe a generic hit is similar to music, maybe music is its own animal.  


Ways to expand on music data:
* Most viewed vevo videos of all time (estimated to add 100)
* Country, hip hop, pop, etc. hits (feels time intensive)
* Do some additional searching from billboard or spotify to get specific songs, artists
* Sourt by relevance instead (probably good for another 500)
* Branch out from artists in top scoring (would help establish non-hit basis so I'm not overfitting Psy songs, for example. probably adds 2000 records easy)
* Look at related search terms like remix, lyric video, etc, which would also expand the discussion to identify how people look for music.

Filling in 'uninteresting' data
YouTube offers a generic search format. By looking at random regex strings

 There may be some duplicates in there, so I will have to consider how to treat those. I'm fine with including the same song twice.

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
