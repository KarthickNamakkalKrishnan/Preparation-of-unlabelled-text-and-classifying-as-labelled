# Preparation-of-unlabelled-text-and-classifying-as-labelled using random forest classifier
This model is built for a business requirement to make the labelling automated using machine learning techniques. The dataset is preprocessed and made with label using re package and split function. 
The punctuations are removed using string.punctuation function and stopwords are also removed. 
Now the words are converted to vector using countvectorizer with N-gram model 
Random forest classifier is used for classification and k-fold cross validation is used to prevent overfitting. 
