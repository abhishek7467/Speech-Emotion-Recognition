# Speech-Emotion-Recognition

Dataset link



https://www.kaggle.com/code/myr9988/speech-emotion-recognition






Speech Emotion Recognition (SER)

Speech Emotion Recognition (SER) is one of the most challenging tasks in speech signal analysis domain, it is a research area problem which tries to infer the emotion from the speech signals. The importance of emotion recognition is getting popular with improving user experience and the engagement of Voice User Interfaces (VUIs). For example, customer services, recommender systems, and healthcare applications.

Objective:

In this mini project,Building and training simple Speech Emotion Recognizer that predicts human emotions from audio files using Python, Sci-kit learn, librosa, and Keras. firstly, we will load the data (Ravdess dataset), extract features (MFCC) from it, and split it into training and testing sets. Then, we will initialize two models (MLP and LSTM) as emotion classifiers and train them. Finally, we will calculate the accuracy of our models.

The whole pipeline is as follows (as same as any machine learning pipeline):

(1)Loading the Dataset: This process is about loading the dataset in Python which involves extracting audio features, such as MFCC
(2)Training the Model: After we prepare and load the dataset, we simply train it on a suited model.
(3)Testing the Model: Measuring how good our model is doing.
