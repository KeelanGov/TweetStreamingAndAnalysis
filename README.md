# TweetStreamingAndAnalysis
Streaming live tweets from twitter surrounding a specific topic (coid19/corona virus) and storing in a MySQL database for further analysis.

Tweets are streamed based on mentions on the word corona virus/covid19.
These tweets are then stored in a csv and MySQL database (semi-structured vs structured) as part of a project guidline.
The tweets are then analysed: 
 - Visualizing the most used hashtags (surrounding the topic) in order to gather what areas of covid are being talked about or mentioned. 
 - The number of tweets over time.
 - The types of sources used to access Twitter.
The actual content of the tweets are then investigated (after cleaning) to gather:
 - Average word count
 - Misspelled words
 - Offensive words
 - Sentiment analysis (non-ML)
