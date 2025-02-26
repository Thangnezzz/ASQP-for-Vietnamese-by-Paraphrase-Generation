# Aspect Sentiment Quad Predictions for Vietnamese Gameshow Comments on Youtube by Paraphrase Generation
Reality shows have become an indispensable part in many people’s lives, it brings joy to many people. Some researchers have tried to use machine learning to exploit this data to apply to real life. In many studies before NLP models have been used to experiment but traditional sentiment analysis can not detect the aspect of the entity, they can not optimize and exploit the full value contained in the data and Aspect-based sentiment analysis appeared. Aspect-based sentiment analysis has become popular in recent years and as an instinct humans are always searching for a challenge to improve what they have .In recent years, researchers have created a new approach to Aspect-based sentiment analysis called Aspect sentiment quad prediction. Existing studies usually consider the detection of partial sentiment elements, instead of predicting the four elements in one shot including the aspect category, aspect term, opinion term, and sentiment polarity. In this project, we present a data set for Aspect sentiment quad prediction task about one of the most popular shows in Vietnam called Rap Viet.

## Dataset
Our dataset was collected on Youtube videos about Rap Viet season 3 by using Youtube API provided by Google and Selenium library in Python. We chose Rap Viet because it is the most popular competitive reality show in Vietnam, it has many controversies from the viewers about many entities that appear in the show. Our dataset includes 3033 comments crawled from a playlist including 118 videos about Rap Viet in season 3. About sentiment polarity, we design it with 3 labels: Positive, Negative and Neutral. For the aspect category detection, we design this subtask with 8 aspects including: Candidate voice, Candidate flow, Candidate general, Candidate dancing, Examiner general, Show stage, Show general and Music. We also have an aspect named Others to detect spam or comments that do not have any aspect or sentiment.

See dataset [here](https://www.kaggle.com/datasets/cthng123/as-quad-predictions-vietnamese-dataset) 
