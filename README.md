# Translator
This repository contains the python code for a translator using keras

This is German to English translator using Keras

Dataset: [deu.txt from Kaggle](https://www.kaggle.com/kuldeepsingharya/german-to-english-translation/activity)

Model: Seq2Seq

There are two measure components of Seq2Seq:
1. Encoding: Done using Embedding Layer and LSTM Layer
2. Decoding: Done using LSTM layer and Dense Layer
 
Optimizer: RMSProp (it works well with RNN)

Loss Function: SparseCategoricalCrossEntropy (uses the input as it is rather than one-hot encoded input)
