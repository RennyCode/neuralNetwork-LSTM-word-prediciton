## neuralNetwork_LSTM_word_prediciton
This project is an implementation of a language based on LSTMs.
Using the Keras library we build different types of models and show the possibilities for language models.

## Workflow
- Import relevant libraries and datasets
- Prepare the data
- Build and train models based on lstms
- Demonstration of the usage of language models

## Models
In this notebook we prepare 4 distinct models:
- M1 - single LSTM layer with forward prediction
- M2 - single LSTM layer with backward prediction
- M3 - two LSTM layers with forward prediction
- M4 - two LSTM layers with backward prediction


## Data preparation
We edit our dictionary to contain all the words of the dataset and add symbols for practical prediction such as a start sentence symbol, end sentence, unknown symbol.
Also we sample the sentences of the dataset in a way that we will create our target by moving the sentence one word forward.


## Usage
- Predict the next word.
- Predict a sentence by continues prediction upon the next word.
- Calculate probability for a prediction of a specific word.
- Calculate probability for a prediction of a specific sentence.


<div style = "padding-bottom: 150; padding-top: 150;">
  <p align="center">
    <img src="/lstmImg.png"  style = " height: 350;  display:block; width:50%;"/>

</div>

## Theory on one leg
LSTM is an advance model that's build on the RNN work idea, to complication of LSTM produce better result in Language models.
The LSTM network allows the model to remember the history input of word and also has the ability of cleaning the model history by forgetting information, in so simulating a word prediction based on the examples that the model has seen.
Each LSTM unit contains 4 neurons that assure those abilities, a simple lstm network tends to preform well only under simple condition but enough to demonstrate the idea.
