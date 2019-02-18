# Sentiment Analysis using LSTM model with Scikit-learn and Keras
## **Dataset**
First GOP Debate Twitter Sentiment
About this Dataset
This data originally came from [Crowdflower's Data for Everyone library](http://www.crowdflower.com/data-for-everyone).

As the original source says,
We looked through tens of thousands of tweets about the early August GOP debate in Ohio and asked contributors to do both
sentiment analysis and data categorization. Contributors were asked if the tweet was relevant, which candidate was mentioned,
what subject was mentioned, and then what the sentiment was for a given tweet. We've removed the non-relevant messages from
the uploaded dataset.

## **Details about model**

 - model contains 3 layers (Embedding, LSTM, Dense with softmax).
 - Upsampling is used to balance the data of minority class.
 - Loss fuction with different class weight in keras to further reduce class imbalance.

## To Do 
- Add requirement.txt
- Add bash script to install required packages 
