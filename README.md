# SentimentAnalysis
#Project # 1
The project performs sentiment analysis on description of vidoes posted on Sweden Youtube official channel. https://youtube.com/@sweden

Firstly data is acquired using request API method in json format which is then filtered to required fields and saved as a dataframe. The dataframe constitue videoId,title, description, viewCount, LikeCount, CommentCount columns.

Initially a generic world cloud is generated using description column of dataframe. 

![wc1](https://github.com/SMKProj/SentimentAnalysis/assets/85155952/025fdab0-6cd1-4b8f-a4d0-4b5ed60a267f)

Later ploarity of texts given in description field is computed using TextBlob package. Polarity assigns a range of values between -1.0 to 1.0, where -1.0 represents most negative and 1.0 refers to most positive text. The word clouds for most positive, less positive and less negative polarities are generated. Words with most negative polarity was not found in given description text.



![wc2](https://github.com/SMKProj/SentimentAnalysis/assets/85155952/f2ce0d3d-0e37-493e-a3a8-e623fbd0f4e7)




Later bar plot for 5 most liked and 5 least liked videos are plotted using plotly.

![5mostliked](https://github.com/SMKProj/SentimentAnalysis/assets/85155952/a442d0d5-3217-42fd-bb71-1c1682e482f9)

![5 leastliked](https://github.com/SMKProj/SentimentAnalysis/assets/85155952/c28d0597-7bb2-4e27-831f-90c8ae0744b6)


#Project # 2
The project is implemented to analyze polarity of comments text in a given dataset and usage of emoticons in given comments text. i. API request call ii. Data Preparation and filtration iii. Data Visualization

![wc](https://github.com/SMKProj/SentimentAnalysis/assets/85155952/7fda0a31-1623-4523-a7fe-bd5f49390f4b)

![emoticonsbarchart](https://github.com/SMKProj/SentimentAnalysis/assets/85155952/fd68d701-2192-41e1-8c71-60907441db2a)


