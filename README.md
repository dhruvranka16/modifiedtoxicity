# modifiedtoxicity
Jigsaw Toxic Comment Classification
Description
This repository contains the code for classifying comments into various types of toxicity like toxic, severe toxic, obscene, threat, insult, and identity hate. The model is trained on the dataset provided in the Jigsaw Toxic Comment Classification Challenge. The main goal of this project is to build a model that can accurately identify and classify toxic comments to make online conversations more constructive and respectful.

Prerequisites
Python 3.x
Keras
Pandas
NumPy
Matplotlib

Model Architecture
Input: Tokenized and padded text sequences
Embedding Layer: Converts tokenized text into dense vectors
LSTM Layer: Processes the sequence data
GlobalMaxPool1D Layer: Reduces the dimensionality of the LSTM's output
Dense Layers: Fully connected layers for classification
Output: Six probabilities representing the likelihood of each type of toxicity
