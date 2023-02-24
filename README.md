## neuralNetwork_LSTM_word_prediciton
This project is a implementaion of a language based on LSTMs.
Using the Keras libary we build different types of models and show the possibilities for language models.

## Workflow
- Import relevant libaries and datasets
- Prepare the data
- Build and train models based on lstms
- Demonstration of the usage of language models

## Models
In this notebook we prepare 4 distinc models:
- M1 - single lstm layer with forward prediciton
- M2 - single lstm layer with backward prediciton
- M3 - two lstm layers with forward prediciton
- M4 - two lstm layers with backward prediciton


## Data preparation
We edit our dictionary to contain all of the word of the dataset and add symboles for practical prediction such as a start sentence symbol, end sentence, uknknown symbol.
Also we sample the sentences of the dataset in a way that we will create our target by moving the sentence one word foward.


## Usage
- Predicit the next word.
- Predicit a sentence by continues prediciont upon the next word.
- Calculate probalility for a prediction of a specific word.
- Calculate probalility for a prediction of a specific sentence.


<div style = "padding-bottom: 150; padding-top: 150;">
  <p align="center">
    <img src="/lstmImg.png"  style = " height: 350;  display:block; width:50%;"/>

</div>

## Theory on one leg
Lstm is a advance model thats build on the RNN work idea, to complication of LSTM preduce better resuslt in Language models.
The lstm network allows the model to remember the history input of word and also has the ability of cleaning the model history by forgetting imformation, in so simulating a word prediction based on the exmaples that the model has seen.
Each lstm unit contains 4 neurons that assure thouse abilities, a simple lstm network tends to preform well only under simple condition but enough to demonstrate the idea.
