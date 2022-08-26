# SPAM or HAM
This project is a part of the **Pattern Recognition and Machine Learning Course (CS5691) at I.I.T Madras**. We Implemented a spam filter from scratch using two popular machine learning algorithms: **SVM** and **Naive Bayes**. The dataset for training was adapted from the CALO project. We achieved an accuracy of 95.5% using SVM and 67% using the Naive Bayes classifier.

The code can be run either from scratch or using the pretrained model:
From scratch:	
1. Download the training set from https://drive.google.com/file/d/13aqN_JmFwAJUmebhIhMPBTSOpUGBp9cp/view?usp=sharing and move to resources folder
1. Copy test mails to 'test' folder
2. Folder 'enron1' contains training and cross-validation emails
3. TRAINING PHASE- Run the scripts in the following order
	- Run 'collection_frequency_creation.py'
	- Run 'vocabulary_and_training_set_creation.py'
	- Run 'cross_validation_set_creation.py'
	- Run 'train_svm_classifier.py'
4. TESTING PHASE- Run 'main.py' to predict emails in test set.
	


