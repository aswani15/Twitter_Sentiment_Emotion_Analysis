# Twitter_Sentiment_Emotion_Analysis
Emotional and Sentiment Analysis on Sachin Using Twitter data

Twitter data starting from Jan 1 2017 till Aug 1 2017 is considered for this analysis. Sentiment analysis will only provide whether the overall sentiment regarding product/brand is positive or Negative. This is not quite useful for companies as positive or negative will not help companies to decide future action. 
If the algorithm can actually capture the sentiment along with emotions like Anger, Sad, Surprise, Anticipation e.t.c it will be easier for business to take correct decisions.

Current attempt is to capture users emotions and sentiment on Sachin Tendulkar. Twitter data starting from 1 Jan 2017 till 1 Aug 2017 is used. Tweets are captured using below Hashtags 


#godofcricket

#sachinsachin

#sachintendulkar

#tendulkar

#thankyousachin


Stopwords are used to remove unnecessary words. “syuzhet” package is used to capture the emotion. Along with stop words non English words which essentially are the hindi/un essential words are removed from the corpus using “hunspell” package


