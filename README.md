Fake News Detection:
- the dataset contains articles that needs to be determined whether they should be a reliable source of information or not.
- i built a model that takes the features as follows: (bag of words):12,000 word using tdidf,(Noun Count and Verb Count) :per article range of Values bet 0-1, (authors): famous authors and their involvement with the article; so that if an author appeared to have been involved with multiple fake articles in the training list the model would be careful when faced with one of his articles in the training set.
- Validation set scores:
 -  Multinomial Naive Bayes scored : 91.9%
 -  Logistic regression scored : 96.7% 
