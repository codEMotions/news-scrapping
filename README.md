# news-scrapping
scrapping with mongooseDB

Using Mongoose and Cheerio (which "parses markup and provides an API for traversing/manipulating the resulting data structure"), this app
was made to scrape articles from the web (in this case, the New York Times). Web scraping is a common feature for consolidating data 
analysis by grabbing web trends. However, in this case, it will be used to simply grabbing articles for personal use. First, the server
will be run from my terminal:

![screenshot of server being run](https://i.imgur.com/VPUGk6X.png)

Then the app will be loaded through the locally provided port:

![screenshot of app](https://i.imgur.com/jVkB7IP.png)

Using the "scrape new article" button click in the header, an article from the NYT will appear and show an article where you will have the option to add notes to the article or remove it entirely from your saved list. 

The saved articles will be qued under Mongo's "headlines". 
