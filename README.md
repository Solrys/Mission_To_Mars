# Mission_To_Mars
Creating an HTML site from Webscraping Nasas Website

## Method
* Flask
* MongoDb
* HTML
* Jupyter Notebook


Flask web application scrapes websites for data related to the Mars Mission and displays the information in a single HTML page.

## Background

I have created an HTML website that scrapes and converges data from multiple sites onto one site with a mobile app as well. 

The code I wrote is designed to grab the most recent data, so if it's run at a later time, all of the results will have been updated without needing to alter the code.

I chose MongoDb over SQL. SQL isn't a good option because it works with tabular data, and only one of the items I scraped is presented in that format. Even then, it's all condensed into a block of HTML code.
I needed a database that works differently from SQL with its neatly ordered tables and relationships. Mongo, a NoSQL database, is designed for exactly this task. MongoDB is a non-relational database that stores data in Binary JavaScript Object Notation (JSON), or BSON format. We'll access data stored in Mongo the same way we access data stored in JSON files.



With the code I wrote I will be able to pull a great image, the most recent news article summary, and even an HTML table. Compared to SQL's orderly relational system, where each table is linked to at least one other by a key, the data we've helped Robin gather is a bit chaotic. This is where a non-relational database comes in.


