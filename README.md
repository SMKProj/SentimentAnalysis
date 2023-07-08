# SentimentAnalysis

The project performs sentiment analysis on description of vidoes posted on Sweden Youtube official channel. https://youtube.com/@sweden

Firstly data is acquired using request API method in json format which is then filtered to required fields and saved as a dataframe. The dataframe constitue videoId,title, description, viewCount, LikeCount, CommentCount columns.

Initially a generic world cloud is generated using description column of dataframe. Later ploarity of texts given in description field is computed using TextBlob package. Polarity assigns a range of values between -1.0 to 1.0, where -1.0 represents most negative and 1.0 refers to most positive text. The word clouds for most positive, less positive and less negative polarities are generated. Words with most negative polarity was not found in given description text.

Later bar plot for 5 most liked and 5 least liked videos are plotted using plotly.
