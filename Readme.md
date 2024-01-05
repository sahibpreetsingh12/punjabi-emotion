# Punjabi Emotion Classifier Transformer Model

This repo conatins steps on how to create your Transformer model for Punjabi Language which is a Indic language with more than 25 million 
speakers.

# Steps
1. Data Collection - For the purpose of data collection i have collected data from websites of punjabi newspapers by scrapping content 
from them.

2. Data Cleaning -  For the Data Cleaning I have used appropriate functions to clean text we have scrapped from websites.

3. Data Handling and Data crunching - For data handling we have used pytorch classes to handle data.

## Creating Neural networks for Fine Tuning

1. We will be creating a neural network with the RobertaClass.
2. This network will have the Roberta Language model followed by a dropout and finally a Linear layer to obtain the final outputs.
3. The data will be fed to the Roberta Language model as defined in the dataset.
4. Final layer outputs is what will be compared to the Sentiment category to determine the accuracy of models prediction.
5. We will initiate an instance of the network called model. This instance will be used for training and then to save the final trained 
model for future inference.

Disclaimer - For complete acces to notebook alongside click [here](https://www.kaggle.com/code/sahib12/punjabi-emotion-data-v3)
