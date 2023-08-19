# SMS-Spam-Collection-prediction-


summary in this project predicts if any messages or email is spam or not ?

python packages : 

1) numpy
2) pandas
3) sweetviz
4) matplolib.pyplot
5) seaborn
6) string
7) from sklearn.feature_extraction.text import CountVectorizer
8) from sklearn.naive_bayes import MultinomialNB
9) from sklearn.model_selection import train_test_split

Questions:

1) Give an overview about the data?
2) Check for missing values and clean it?
3) Get a statistical summary about the data?
4) use sweetviz to get auto analysis and visualization?
5) Make a histogram between the length and its frequency ?
6) Map the labels to make ham= 0 and spam = 1 ?
7) Make two histogram about the length based on the label ?
8) Make a pie chart of SMS label distribution?
9) Convert all strings to their lower case form?
10) Remove all punctuations?
11) make every sentence in list ( tokenization)?
12) Get the count frequencies of each word to convert the string into numeric?
13) Get all the words using count vectorizer into an array?
14) fit the count vector with the documents or emails or messages ?
15) get the feature names out from the count vector ?
16) convert the doc array when transforming the count vector and convert it into array?
17) Make a frequency matrix by making the data is doc array and columns is the feature named of the count vector ?
18) train the model and use count vectorizer with the train data and test data?
19) use naive bayes (multinomialNB) and fit the model with x_train and y_train?
20) Get the prediction and get the accuracy score and percision score and f1 and recall score?
21) use pipeline to make two steps vectorizer and nb?
