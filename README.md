# Fake news detection using Support Vector Machine
 
This is a Machine Learning model to predict whether a Tweet describing news events is fake or real based only on the post description and other metadata, thus the ML model would be a text classifier and it will not process images. The problem is very similar to the 2015 MediaEval challenge which takes into consideration both images and text to recognise viral fake news. 

The data available for training the ML model consists of CSV tweet datasets from the 2015 MediaEval Challenge. The majority of these social media posts describe several events such as Hurricane Sandy and Boston Marathon bombings.

The success metric for this ML model is the micro F1-score (accuracy). This score is a value between 0 and 1, the latter indicates the best precision and recall.
## Results
- Linear SVM with CountVectorizer (Accuracy: 0.82)
- Linear SVM with TF-IDF Vectorizer (Accuracy: **0.88**)

## References

**MediaEval 2015** - [http://www.multimediaeval.org/mediaeval2015/verifyingmultimediause/](http://www.multimediaeval.org/mediaeval2015/verifyingmultimediause/)

