# Automatic-Essay-Grading_NLP
The project aims to build an automated essay scoring system using a data set of ≈13000 essays from kaggle.com. These essays were divided into 8 dierent sets based on context. We extracted features such as total
word count per essay, sentence count, number of long words, part of speech counts etc from the training set
essays. We used a linear regression model to learn from these features and generate parameters for testing and
validation. We used 5-fold cross validation to train and test our model rigorously. Further, we used a forward
feature selection algorithm to arrive at a combination of features that gives the best score prediction.
