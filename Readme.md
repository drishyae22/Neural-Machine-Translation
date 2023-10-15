NEURAL MACHINE TRANSLATION


Problem Statement: 
Given the dataset consisting of French sentences and corresponding English sentences, the task was to build ANN model to translate sentences from French to English.


Objective:
The data consisted of 1,97,463 sentences. I randomly chose 10,000 sentences for training and 3,000 sentences for testing to reduce training time and overfitting. The task was to predict the English sentences corresponding to French sentences.


Goals Achieved:
* I did tokenization and padding on the sentences, followed by one hot encoding required for the ANN model.


* I created a LSTM model consisting of an Embedding layer followed by LSTM layer, Repeat Vector layer and finally a Time Distributed Dense layer for predicting English sentences corresponding to French sentences.


* The model gave training accuracy of 95.33% and validation accuracy of 71.68%.
