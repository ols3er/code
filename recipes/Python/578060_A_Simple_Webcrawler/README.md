## A Simple Webcrawler  
Originally published: 2012-03-03 02:31:44  
Last updated: 2012-03-03 02:37:30  
Author: John   
  
This is my simple web crawler.  It takes as input a list of seed pages (web urls) and 'scrapes' each page of all its absolute path links (i.e. links in the format http://) and adds those to a dictionary.  The web crawler can take all the links found in the seed pages and then scrape those as well.  You can continue scraping as deep as you like.  You can control how "deep you go" by specifying the depth variable passed into the WebCrawler class function start_crawling(seed_pages,depth).  Think of the depth as the recursion depth (or the number of web pages deep you go before returning back up the tree).