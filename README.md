Fake-Reviews-Detection
Problem Statement
Detection of fake reviews out of a massive collection of reviews having various distinct categories like Home and Office, Sports, etc. with each review having a corresponding rating, label i.e. CG(Computer Generated Review) and OR(Original Review generated by humans) and the review text.

Main task is to detect whether a given review is fraudulent or not. If it is computer generated, it is considered fake otherwise not.

Description
Description: The generated fake reviews dataset, containing 20k fake reviews and 20k real product reviews. OR = Original reviews (presumably human created and authentic); CG = Computer-generated fake reviews.

Python Libraries and Packages Used
Numpy
Pandas
Matplotlib.pyplot
Seaborn
Warnings
nltk
nltk.corpus
String
sklearn.naive_bayes
sklearn.feature_extraction
sklearn.model_selection
sklearn.ensemble
sklearn.tree
sklearn.linear_model
sklearn.svc
sklearn.neighbors
Techniques Used for Text Preprocessing
Removing punctuation character
Transforming text to lower case
Eliminating stopwords
Stemming
Lemmatizing
Removing digits
Transformers Used for Text Vectorization, Weighting and Normalization
CountVectorizer Bag of Words Transformer
TFIDF(Term Frequency-Inverse Document Frequency) Transformer
Machine Learning Algorithms Used
Logistic Regression
K Nearest Neighbors
Support Vector Classifier
Decision Tree Classifier
Random Forests Classifier
Multinomial Naive Bayes
Performance Overview of ML Models Leveraged
Support Vector Machines Classifier performed the most accurate predictions regarding the fake nature of reviews having a predictive accuracy of just over 88%, closely followed by Logistic Regression which had a prediction accuracy of a little more than 86%. Random Forests Classifier and Multinomial Naive Bayes algorithm predicted to a precision level of approximately 84%. However, the Decision Tree Classifier performed fake reviews prediction upto an accuracy of just over 73%. The worst performing algorithm was the K Nearest Neighbors algorithm which could only perform the predictions upto an accuracy level of nearly 58%.

