# Anatomy of a YouTube video
Analysis of YouTube videos and genres.

## Summary

What makes people find and click on music on YouTube? Does the way a video is posted have anything to do with how popular it gets? In parts 1-3, I try and partly succeed in predicting how big a music-type video will get. For parts 4-6, I end up pivoting to identifying the most engaging video tags, in an effort to optimize engagement per view for a potential advertiser. In the end, I try to answer the age-old question: What the hell is trap music, actually?

<a href=https://conorbarryhoke.github.io/>Click here<a> for the presentation.
A more detailed write-up on ETL through Regression is included in the background folder.

<a href=https://public.tableau.com/profile/conor.barry.hoke#!/>Tableau Profile<a> showing summary of genre and engagement metrics

## Workflow
The ultimate final outputs of this project are mainly contained in <strong>Classification_Engagement</strong>.

There are two diverging paths in here. Originally, the project was an attempt to predict views, and so the Regression model was the final endpoint. Once this was hit, I started from the same source data and began looking at engagement by genre. The workflow looks likes this:

<span><img src="https://raw.githubusercontent.com/conorbarryhoke/Capstone/master/assets/prime_workflow.bmp"><span>



Refer to /background/ for feature dictionary csv and full workflow diagram (Supplemental Excel)



To support the prime workflow, the folder structure and associated data files is as follows:

<span><img src="https://raw.githubusercontent.com/conorbarryhoke/Capstone/master/assets/folder_organization.bmp"><span>

The files are referenced like this:
<span><img src="https://raw.githubusercontent.com/conorbarryhoke/Capstone/master/assets/workbooks_summary_sources.bmp"><span>

See /data/ for more information on the data files themselves.

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
