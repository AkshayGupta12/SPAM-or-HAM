The code can be run either from scratch or using the pretrained model:
From scratch:	
	1. Copy test mails to 'test' folder
	2. Folder 'enron1' contains training and cross-validation emails
	3. TRAINING PHASE- Run the scripts in the following order-
		(a) Run 'collection_frequency_creation.py'
		(b) Run 'vocabulary_and_training_set_creation.py'
		(c) Run 'cross_validation_set_creation.py'
		(d) Run 'train_svm_classifier.py'
	4. TESTING PHASE- Run 'main.py' to predict emails in test set.
	
Pretrained model:
Note: This might not work if the scikit version and other dependencies are different from that used when compiling the code and creating the models.
	1. Copy test mails to 'test' folder
	2. Run the main.py.



