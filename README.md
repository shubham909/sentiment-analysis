
# Tweets on Indian Railways:
  * Over 2000 Tweets have been fetched for the query '@RailMinIndia' using twitter api.
  * Extracted tweets consisted mostly of complaints and anouncements about railways.  

# Pre Processing:
As tweets generally contained a lot of unwanted texts like- **RT, @handle, punctuations, emojis, hashtags and url**. This needed sufficient cleaning before any further use of data.  

# Parameters considered:
  * **Punctuality**
  * **Safety**
  * **Food**
  * **Cleanliness**
  
# Sentiment Analysis:
  * **Positive**: For showing positive sentiment towards the parameter.
  * **Negative**: For showing negative sentiment towards the parameter.
  * **Neutral**: For showing neutral sentiment towards the parameter.
  
  For classification, sentiment property of **TextBlob** was used which returns *polarity* which is a float value within the range [-1.0, 1.0] where -1 is a -ve sentiment and +1 is a positive sentiment. 
  
#  Future Work:
  * Building a cassifier for Hindi tweets.
  * A custom classifier can be used for better accuracy.
