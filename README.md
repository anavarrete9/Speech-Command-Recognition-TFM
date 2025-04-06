# Speech-Command-Recognition-TFM

This repository is intended to show the code developed while doing a Master's Thesis in Speech Command Recognition, using the dataset Speech Command Recognition v0.02.

First small tryouts are done with CNN, RNN, LSTM and GRU using a smaller dataset A, using different types of audio data (log-mel-spectrogram and MFCC, with two different hyperparameters each).

After choosing the best type of model (GRU) and the type of data and hyperparameter (log-mel-espectrogram, n_mel=64), for which the model works best, new tryouts are carried out using dataset B (bigger and A) and dataset B.1 (data set B + data augmentation via noise addition).
