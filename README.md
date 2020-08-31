# Detecting-Bullying-Twitter
Detecting traces of bullying in Twitter posts using machine learning and natural language processing

Read our complete research paper here: https://link.springer.com/chapter/10.1007/978-3-030-22871-2_56

Or on Research Gate: https://www.researchgate.net/publication/333948566_Detecting_Traces_of_Bullying_in_Twitter_Posts_Using_Machine_Learning

We have also included a PDF version in the repository. 

File Decriptions: 

TFIDF_Model.ipynb: Includes code for creation of the Term Frequency-Inverse Document Frequency model and evalutation of the model through a confusion matrix and a receiver operating characteristic curve. 

Frequency_Stopwords.ipynb: Frequency and keyword analysis of Tweets to get a better understanding of words that commonly appear in bullying/non-bullying related Tweets. Removes stopwords to focus on noncommon words. 

Graphs_Statistics.ipynb: Uses user account data to create graphs and conduct statistics tests to test relations between account metadata and bullying/non-bullying related activity. 

DEMO.ipynb: Runs our demo of predicting tweets in real-time.

models/: contains files of our trained models

