# CODTECH-2
NAME : MANTHANI TARUN

COMPANY : CODTECH

DOMAIN: DATA ANALYTICS

DURATION : FEBRUARY 6

overview of the project



  PROJECT:  SOCIAL MEDIA SENTIMENT ANALYSIS  


 Analyze social media data (e.g., Twitter) to understand public sentiment
 towards specific topics, products, or events. Use natural language
 processing (NLP) techniques to preprocess text data, extract sentiment
 scores, and visualize sentiment trends over time

 What is sentiment analysis?
 
Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining , deriving the opinion or attitude of a speaker.



 Why sentiment analysis?

 Business:
     In marketing field companies use it to develop their strategies, to understand customers’ feelings towards products or brand, how people respond to their campaigns or product launches and why consumers don’t buy some products.
    Politics:
    In political field, it is used to keep track of political view, to detect consistency and inconsistency between statements and actions at the government level. It can be used to predict election results as well!
    
 Public Actions: 
    
  Sentiment analysis also is used to monitor and analyse social phenomena, for the spotting of potentially dangerous situations and determining the general mood of the blogosphere. 



   We follow these 3 major steps in our program:

 Authorize twitter API client.
 Make a GET request to Twitter API to fetch tweets for a particular query.
 Parse the tweets. Classify each tweet as positive, negative or neutral. 

Tokenize the tweet ,i.e split words from body of text.


Remove stopwords from the tokens.(stopwords are the commonly used words which are irrelevant in text analysis like I, am, you, are, etc.)


Do POS( part of speech) tagging of the tokens and select only significant features/tokens like adjectives, adverbs, etc.


Pass the tokens to a sentiment classifier which classifies the tweet sentiment as positive, negative or neutral by assigning it a polarity between -1.0 to 1.0 .


TextBlob uses a Movies Reviews dataset in which reviews have already been labelled as positive or negative.


Positive and negative features are extracted from each positive and negative review respectively.


Training data now consists of labelled positive and negative features. This data is trained on a Naive Bayes Classifier . 


   ![Screenshot 2025-01-17 225242](https://github.com/user-attachments/assets/501f6231-33fa-4897-a221-77bb4bcaac4c)
![Screenshot 2025-01-17 225230](https://github.com/user-attachments/assets/b53ba426-e2da-4c1c-b475-a9fa8be29f4a)




 
