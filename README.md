# Data-mining-from-using-twint

In this project i have analysed data of influencers ,extracted their tweets, Filtered tweets based on min likes, min retweets,

and min replies,tweets contain specific hashtags and saved them in a csv file

# Data Cleaning

I have also extracted latest covid 19 data cleaned it by

 ## 1. Removing punctuation
 Tweet data we scrapped consists of punctuations, hashtags, special characters, emojis etc.
 First I will remove the punctuations hashtags etc from the tweet. 
 Here I will replace everything except characters and numbers with spaces
 
 ## 2.Tokenization
 Tokenization involves chopping a text into pieces, called tokens. Here I am creating a function for tokenization. 
 In addition I am converting all text in lowercase.
 If we have covid and COVID computer will think them as two different words. 
 So there will be duplication of data. Therefore, I am converting text to lowercase
 
 ## 3.Removing stopwords
 Stop words are commonly used word ( such as a, an, the, in, on). 
 During analysis these words does not have much value to the analysis.
 As a result, we remove these words.
 
 ## 4. Stemming / Lemmatize
 Here I am using stemmer as this is fast compared to lemmatize. There is different stemmer.
 Here I am using Porter stemmer as this is most popular and commonly used stemmer
 
# Visualization of data

To visualise the result,  Here I used  seaborn Library

# To Install
Twint works best with python 3.6
install python 3.6 
and then install twint in its environment
for more information how to install twint
https://github.com/twintproject/twint
