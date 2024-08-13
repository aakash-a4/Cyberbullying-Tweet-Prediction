# cyberbullying-tweet-prediction

This project predicts the nature of the tweet into 6 Categories.

* Age
* Ethnicity
* Gender
* Religion
* Other Cyberbullying
* Not Cyberbullying

## Tools and Technologies  
**Model:** Used linear Support Vector Machine to classify tweets.  
  

## Methodology
* Downloaded the data from kaggle. [(data)](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification)
* Performed some Exploratory Data Analysis to get the overview of data. [(initial_modelling.ipynb)](https://github.com/apurvayadav/cyberbullying-tweet-recognition-app/blob/main/initial_modelling.ipynb)
*  Created a Word Cloud from the data.
*  Performed the necessary steps for textual analysis.
    * Removing Stopwords, puctuations, URLs, etc
    * Performed Stemming and Lemmatization.
* Automated the process of preprocessing by creating functions. Which would be helpful in predicting Custom Outputs.


## References
* Twitter Sentiment Analysis- A NLP Use-Case for Beginners - [https://www.analyticsvidhya.com/blog/2021/06/twitter-sentiment-analysis-a-nlp-use-case-for-beginners/](https://www.analyticsvidhya.com/blog/2021/06/twitter-sentiment-analysis-a-nlp-use-case-for-beginners/)
5372-Article Text-9814-1-10-20210513 (1).pdf
Cyber Bullying Detection for Twitter Using ML Classification Algorithms (ijraset.com)
Cyberbullying severity detection: A machine learning approach | PLOS ONE
GitHub - dhavalpotdar/detecting-offensive-language-in-tweets: Detecting cyberbullying in tweets using Machine Learning
