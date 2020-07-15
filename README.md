# NNFL-Lab2-CNN
Build a Convolutional Neural Network for Multiclass Classification

# Discription
This is a 6-class image classification task. Predict your classes as {0, 1, 2, 3, 4, 5} .
Labels are expected to be integer(int) type, so if you plan to use regression or any other method, round off the values to integer type only!

Only 10 submissions per day are allowed

Usage of Pre-trained model weights is prohibited and if used, will be penalised.

Solution is expected to be an Convolutional Neural Network, with no restriction on the framework used (Keras, Tensorflow, caffe, Pytorch, what-not).

Verify the usage of any libraries and other doubts with the TAs in the Discussion Forum on kaggle only, so that the announcements and doubts are clarified to everyone.

Weights to be stored for the best submission in a "model.h5" file.

While submitting predictions your target column should be named 'label'
The Submission file should only have 2 columns : ['image_name' , 'label']

All the best, and have fun! 

# Evaluation(Accuracy)

Evaluation metric is Categorization Accuracy.

There are 7301 images in the test set, with a split of 40% for Public Leaderboard and 60% for Private Leaderboard. (40+60) but the overall evaluation would be done for 100% of the data.

Hence, your CSV should contain 7301 rows with { " image_name", "label" } for each row.

Accuracy is one metric for evaluating classification models. Informally, accuracy is the fraction of predictions our model got right.

Accuracy alone doesn't tell the full story when you're working with a class-imbalanced data set, unlike this one, where there is a significant disparity between the number of different class labels.

Since, this dataset isn't fully imbalanced, accuracy does the job. The other metrics you can read up for better performance is Weighted F-1. Usage of classification_report from sklearn is encouraged.
