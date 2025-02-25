# Project Overview: 
This project is for detection of an email whether to be a spam or ham using a support vector machine(SVM) algorithm.

# Project Scenario: 
Emailing has become one of the major communication method for business, advertising and many more, however

# Project Objectives: 

1. Explore and preprocess the data.
2. Create a base line model and receive optimum results.
3. Tune the base line model and providing suggestions for optimum results.

# Data components: 

The data is in a CSV format containing mainly four features:

1. mail_id: A unique id given to each email.
2. mail_hash: A unique combination of characters given to each email.
3. mail_text: Information of the mail sent with the body of the mail.
4. mail_cat: Actual Class of mail (spam/ham).

# Method of approach:

1>.For this detection, the methodology followed is a Bigram SVM classifier which is trained on bigram features for the text classification.

Bigram means using a sequence of two consecutive word in a text rather than single words.

Apart from this, there are many methods of feature extraction for SVM such as TF-IDF, Word Embedding and more, I have used Count Vectorization in this case of scenario.

2>. For preprocessing certain steps are followed: 
a) extraction of possible features using regex
b) removal of unnecessary columns and rows with null check
c) using tokenization to create tokens

3>. A base line model is created along with classification report and AUC-ROC curve.

4>. Tuning was performed using cross-validation. probability factor and bagging model.

# Results: 

1. Gained high accuracy results from base line and tuned model.
2. comparison among the models and gave suggestions what else can be done.
3. Knowledge earned with each steps.

# Files in repo:

|Files...| Description...|
|Bigram.ipynb| Main coding file with approach followed and more elaboration of suggestion and results gained|
|consolidated,csv| Data file used for this project|



  


