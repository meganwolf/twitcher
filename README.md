# TWITCHER-PRIVATE
Comprehensive Feed Searches 

###Twitcher.io


## https://github.com/GirlsFirst/2016_ATT_ATL_TWITCHER <-- less private repository for Girls Who Code 

## Synopsis

This project aims to narrow down Twitter searches to a specific profile / feed with recommended keywords that will assist employers. This is done by searching user timelines, rather than using Twitter's built-in search feature. Regular Expressions is used to search for specified keywords once the user timeline is pulled into a .txt file. 

## Code Example
Get the user's tweets:
user_tweets = t.get_user_timeline(screen_name=twitter_handle, include_rts=True, count=200)

RegEx format:
regex = '"text": "([^"]*(term1|term2|term3|term4|term5|term6)[^"]*)'

## Motivation

According to Time (http://time.com/money/3510967/jobvite-social-media-profiles-job-applicants/),  "Twitter appears to be the platform least used by hiring managers, and is used similarly to Facebook, but with less of an emphasis on candidate vetting." In order to make Twitter more usable for hiring managers, we developed this platform that makes researching candidates on Twitter easier. 

## Installation

To run in terminal: 
pip install twython 
pip install simplejson

Imported Libraries for terminal:
from twython import Twython
import simplejson
import re
import Werkzeug

For Flask:
    <p>pip install werkzeug</p>
    <p>pip install flask</p>
    <p>pip install flask-boostrap</p>

Imported Libraries for Flask: 
    <p>from flask import Flask, render_template, request</p>
    <p>from werkzeug import routing</p>


## API Reference
Twitter API https://dev.twitter.com/overview/documentation through the twython library https://github.com/ryanmcgrath/twython

## Contributors
Lillian Chow and Megan Wolf

## License

if you want to use anything from this repository, please message _____ first.
