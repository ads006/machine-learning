# machine-learning

This dataset summarizes a set of features about news articles published by Mashable in a period of two years, containing information about the articles like word count, images and links present, and popularity (number of shares).

About dataset
Definitions of the columns are found below.
Data dictionary
1. n_tokens_content: Number of words in the content
2. n_unique_tokens: Rate of unique words in the content
3. num_hrefs: Number of links
4. num_self_hrefs: Number of links to other articles published by Mashable
5. num_imgs: Number of images
6. num_videos: Number of videos
7. data_channel_is_entertainment: Is data channel 'Entertainment'?
8. data_channel_is_bus: Is data channel 'Business'?
9. data_channel_is_tech: Is data channel 'Tech'?
10. is_weekend: Was the article published on the weekend?
11. global_subjectivity: Text subjectivity
12. global_sentiment_polarity: Text sentiment polarity (above 0 is towards positive, below 0 is towards negative)
13. title_subjectivity: Title subjectivity
14. shares: Number of shares
15. avg_positive_polarity: Avg. polarity of positive words
16. title_sentiment_polarity: Title polarity

Task 
Stakeholders are interested to automatically detect any article as positive or negative. Build a predictive model which predicts the sentiment polarity of unseen news articles. You may choose to define article polarity as either a numeric or categorical target. Assume the unseen news articles contain all information except global_sentiment_polarity.
