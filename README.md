Twitter-User-Analysis
=====================

Python code to pull user data from twitter.  


## How to run the code

1. git clone https://github.com/swGooF/Twitter-User-Analysis.git
1. cd Twitter-User-Analysis
1. First open getdata.py and enter your Twitter access_token_key, access_token_secret, consumer_key, consumer_secret
1. from a command line 'python getdata.py datascience 3'


## What are the parameters

1. a query string: 'datascience' in the example above
1. Number of pages to return, each page will return 20 users, the current Twitter API is 180 calls per 15 minutes and each page requires a new call


