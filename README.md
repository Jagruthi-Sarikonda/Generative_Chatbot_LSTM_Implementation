# Generative_Chatbot_LSTM_Implementation

## Problem Statement
Building a prototype of (Open Domain)Generative ChatBot using (Endoder-Decoder model) Seq2Seq architecture with LSTM layers using Tensorflow,keras libraries

## Introduction to Seq2Seq Architechchure

This model predicts a word given in the user input and then each of the next words is predicted using the probability of likelihood of that word to occur. In building the Generative chatbot, this approach is used for text generation given in the user input.
The encoder outputs a final state vector (memory) which becomes the initial state for the decoder. Teacher forcing method is used to train the decoder which enables it to predict the following words in a target sequence given in the previous words. 

<p align="center">
  <img src="https://cdn-images-1.medium.com/max/1600/1*bnRvZDDapHF8Gk8soACtCQ.gif" alt="Animated GIF">
</p>

## Advantages of LSTM(Long Short Term Memory)

LSTMs are designed to overcome the vanishing gradient problem, allowing them to capture long-term dependencies in sequential data
The memory cell in LSTM architecture(Forget, Input, Output gates) which allows the network to selectively store and retrieve information
LSTMs can be parallelized during training, which helps in faster convergence compared to traditional RNNs. This is because the computations for different time steps can be performed simultaneously.

![Alt Text](https://github.com/Jagruthi-Sarikonda/Generative_Chatbot_LSTM_Implementation/blob/main/lstm_memory_cell.jpg "LSTM Memory cell")


## Tasks
```
    Task 1: Import Libraries
    Task 2: Data(from Kaggle) Preprocessing and preparing for Seq2Seq model
    Task 3: Defining Encoder-Decoder model
    Task 4: Model Training
    Task 5: Defining Inference Model
    Task 6: Testing the OurModel
```
