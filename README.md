SMS Spam Detection Using Machine Learning
1. Introduction / Objective
The objective of this project is to develop a machine learning system that classifies SMS messages into two categories: spam and ham. The system uses text-processing techniques and the Multinomial Naive Bayes algorithm to identify patterns in messages and predict their categories.
2. Dataset Used
Dataset: SMS Spam Collection
Source: UCI Machine Learning Repository
Dataset link: https://archive.ics.uci.edu/dataset/228/sms+spam+collection
The dataset contains labeled SMS messages that are used to train and evaluate the classification model.
3. Tools & Technologies
•	Python
•	Google Colab
•	Pandas
•	Scikit-learn
•	TF-IDF Vectorizer
•	Multinomial Naive Bayes
•	Matplotlib
•	Joblib
4. Steps / Methodology
1.	Downloaded and loaded the SMS Spam Collection dataset.
2.	Explored the dataset and examined the spam and ham categories.
3.	Divided the data into training and testing sets using an 80:20 split.
4.	Converted message text into numerical features using TF-IDF.
5.	Trained a Multinomial Naive Bayes classification model.
6.	Evaluated the model using accuracy, precision, recall, F1-score and a confusion matrix.
7.	Tested the model with custom SMS messages.
8.	Saved the trained model and TF-IDF vectorizer for reuse.
5. Screenshots of Output 
   6. Conclusion & Learnings
The SMS Spam Detection project demonstrates how machine learning can be applied to text classification. The trained model achieved 97.04% accuracy on the test dataset. Through this project, I gained practical experience in data exploration, text preprocessing, TF-IDF feature extraction, model training, evaluation, and prediction.
The results show that the model can classify many messages correctly, although further testing is needed to understand its limitations and potential misclassifications
