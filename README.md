# web_crawler

Project Task

Create a web crawler using python that is able to scrape first 10,000 results for the following
google search input - site:youtube.com openinapp.co

Collect all the given YouTube links of the above search link.

Give the results in the JSON/CSV format.

Note - Links should be of YouTube channel instead of scraping youtube video links.


You can specify number of records and type of youtube channels to scrape (like marvel movies, ted talks and in this case openinapp)
It will fetche upto 35 google search pages. after that google search engine will check weather you are a robot. or stop you from scrapping the data as repeated use will be flagged as suspicious.

![Screenshot 2023-06-26 164444](https://github.com/siddhantbhagat/web_crawler/assets/41586492/8a1ce4e0-cc77-46b0-9686-81118c558e0c)

make sure you have installed selenium and google driver before running the project.
you might have to run program multiple times as google changes search settings for webscrapping and you won't get "Next" option every time.
