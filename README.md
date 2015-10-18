# TwitterSentimentAnalysis
 This is a project based on finding the sentiment of a tweet simply by classifying it as postive or negative. Based on
 sentdex youtube channel's tutorials, this is an effort to get the basics of text classification via my favourite 
 module in python that is nltk. This combined with a scikit learn module makes a powerful combination of text 
 classification using machine learning. Naive Bayes algorithm used in this project are: nltk's original bayes classifier,
 sklearn's multinomial, bernoulli linear classifiers and finally sklearn's svc, linearsvc and nusvc svm classifier.
 Final verdict is based on a voting system out of all these classifers.
 Integration with tweepy makes it possible to stream live tweets which are saved in a fileand that file makes it possible
 to plot sentiment of the tweets live!!
 
 Future improvements:
 There is a slight negative bias in this classifier which can be improved with better tarining data. Also the classification
 presently is only 2 dimensional, i.e, either positve or negative. Tweets can be classified as neutral also which is another
 dimension that could be incorporated in the project as well.
