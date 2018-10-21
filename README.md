# Capstone
Anantomy of a YouTube video

## Summary

What makes people find and click on music on YouTube? Does the way a video is posted have anything to do with how popular it gets? In parts 1-3, I try and partly succeed in predicting how big a music-type video will get. For parts 4-6, I end up pivoting to identifying the most engaging video tags, in an effort to optimize engagement per view for a potential advertiser. In the end, I try to answer the age-old question: What the hell is trap music, actually?

<a href=https://conorbarryhoke.github.io/>Click here<a> for the presentation.
A more detailed write-up on ETL through Regression is included in the background folder.

<a href=https://public.tableau.com/profile/conor.barry.hoke#!/>Tableau Profile<a> showing summary of genre and engagement metrics

## Workflow
The ultimate final outputs of this project are mainly contained in <strong>Classification_Engagement</strong>.

There are two diverging paths in here. Originally, the project was an attempt to predict views, and so the Reggresion model was the final endpoint. Once this was hit, I started from the same source data and began looking at engagement by genre. The workflow looks likes this:

<span><img src="https://raw.githubusercontent.com/conorbarryhoke/conorbarryhoke.github.io/master/capstone_files/assets/title_text.bmp"><span>

Refer to background for feature dictionary csv.

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
* pickle

Google Project name: "argon-gear-217322"


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
6. Website Design:
https://github.com/BlackrockDigital/startbootstrap-resume.git
