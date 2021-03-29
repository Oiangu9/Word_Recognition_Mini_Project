# Word_Recognition_Mini_Project
Free project made for the Machine Learning subject.

A labelled word recording dataset is explored and used to generate predictive Convolutional Neural Network models for the recognition of these words.

The employed dataset was obtained from Kaggle:

https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/overview

In this dataset, we are offered .wav audio files of different people saying 20 words we would like to recognize:

["Yes", "No", "Up", "Down", "Left", "Right", "On", "Off", "Stop", "Go", "Zero", "One", "Two", "Three", "Four", "Five", "Six", "Seven", "Eight","Nine"]

Some additional audio files are given with background noise, together with some example words that should be classified as "unrecognized":

["Bed", "Bird", "Cat", "Dog", "Happy", "House", "Marvin", "Sheila", "Tree", "Wow"]

Thus, we have a total of 21 classes to classify.
