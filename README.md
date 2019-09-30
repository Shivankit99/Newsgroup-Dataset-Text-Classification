# Newsgroup-Dataset-Text-Classification
Training Dataset and Testing Dataset : http://archive.ics.uci.edu/ml/machine-learning-databases/20newsgroups-mld/
The training dataset consists of 20 different classes each of which have around 1000 articles each . 
The first part of the project was to be able to create the x dataset for training . 
This was done in the following steps : 
1) Each article was parsed one by one .
2) Stop words were removed 
3) A dictionary was created with each word and its frequency.
4) Top 2000 words were selected and used as the feature list .
5) The entire 2d array was initialized with zero and then the entire dataset was parsed again to fill this array .

The second part of the project was using the sklearn implementation of Multinomial Naive Bayes classifier. 

The third part of the project was using a self implemented Naive Bayes classifier. 

