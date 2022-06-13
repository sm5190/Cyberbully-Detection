## Cyberbully-Detection-Classification
# Introduction
Over the last decade, with new technological advancements, cyberbullying has become
one of the most significant issues in the world. This study contributed to introducing a
framework for preventing cyberbullying on SM by detecting bullying textual posts by
employing sentiment analyses and bullying features through the exploration of ML
algorithms. The dataset corpora extracted from Twitter are diverse in content. The
taxonomy designed for bully characteristics covers most of the areas a person is bullied
for such as racism, prejudice against women, disrespectful or insulting words,
aggressiveness, etc. Embedding methods such as BoW and TFIDF have been used on
thoroughly preprocessed tweets for applying selected classifiers namely: Liblinear based
Logistic Regression, Linear SVM, Multinomial Naive Bayes, Random Forest and BiLSTM-RNN with GloVe Embedding. It is
evident from several performance evaluation measures of the models that the Random
Forest model with TFIDF embedding performs better in both cases. The highest achieved
accuracy (F1 score) for the bully identification model is 80.8% and for the bully
classification model is 87.7%



# Proposed Framework
The framework proposed for the prevention of cyberbullying is a prevention measure
generalized for all SM platforms. In the proposed framework, the analytics module shall
automatically analyze user posts/comments through deployed ML models in the cloud
and the decision module shall take action accordingly if a bullying attempt is found. This
framework is targeted to contribute to SM authorities so that monitoring of bullies can be
automatic and certain measures can be taken against the guilty to stop cyberbullying trend
for good.
- **Framework For Cyberbully Prevention**
![image](https://user-images.githubusercontent.com/53345331/173417687-e87d01b9-a15f-47c2-a109-afad33a680e1.png)
- **Protocol of Cyberbully Prevention**
![image](https://user-images.githubusercontent.com/53345331/173417780-14975c33-cb37-40b5-81c7-6f265f33e29f.png)
