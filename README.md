# Twitter Scrapping

Twitter Project by using Snscrape, MongoDB, Streamlit

This app is  for Twitter Scraping by creating a web app using Streamlit. It scrapes the twitter data by using Snscrape library for the given hashtag/ keyword for the given period. The scarped tweets will be uploaded in MongoDB and can be dowloaded as CSV or a JSON file.


**Required Libraries to import**
import pandas as pd
import streamlit as st
import snscrape.modules.twitter as sntwitter
import pymongo
from pymongo import MongoClient
import json
from PIL import Image

**GUI Framework:** 

Streamlit -Web hosting
           

**Scraping the tweet**

Data are scraped using SNscrape of python library, with the help pf TweetSearchScrape() method we can scrape the Twitter data without Twitter API. The method is passed with a query conating the hashtag to be search and the search dates (From start date to end date)


**Uploading data in MongoDB**

  Tweets that are scraped using the Snscrape library is now imported into MongoDB database by creating the client connection (by using MongoDb Atlas) and data's will be stored in the collection.
  

**Creating the GUI**

GUI can be created using streamlit web framework. In this app we can search, display data,about,downlaod data as CSV,Json and upload data's to database.

