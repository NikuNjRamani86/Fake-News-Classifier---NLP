
# Fake-News-Classifier using Natural Language Processing




## Summary

I have used the traditional BoW method on news titles by stemmatizing them and then using countvectorizer with ngram_range=(1,3). After having numerical representation of input, I used classification model for predictions. I experimented with 2 classifiers Multinomial NB (accuracy=90.2%) and the infamous Passive Aggressive Classifier(accuracy = 91.7%). 
After I have used TF-IDF vectorizer for BoW. In this model, I got result like Multinomial NB (accuracy=84.4%) and the infamous Passive Aggressive Classifier(accuracy = 92.1%).