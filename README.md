# Emotion Classifier

[![OpenFaaS](https://img.shields.io/badge/Language-Python-blue.svg)](https://www.openfaas.com)
[![OpenFaaS](https://img.shields.io/badge/Model-AWD_LSTM-green.svg)](https://www.openfaas.com)

## What is the project?
This project aims at classifying the emotion present in the text with the help of NLP and AWD LSTM.

## Dataset
The dataset contains 
- timestamp
- text
- emotions (anger, sadness, fear, joy, love, surprise)

## Requisites
- fastai
- TextLMDataBunch
- TextClasDataBunch
- LanguageModelLearner
- TextClassifierLearner

## Working of the project
1. The dataset is loaded.
2. We create two models. A language model and a text classification model, therefore we create two different data bunches using the TextLMDataBunch and TextClasDataBunch classes.
3. A language model is created using the language_model_learner method. We pass this method three arguments. Our data, a pre-trained model, and a dropout percentage.
4. With the language model ready and the encoder saved, we create a text classification model, load in the encoder, and train the network.
5. The confusion matrix is produced.
## Base Paper
https://www.researchgate.net/publication/225045375_Emotion_Detection_from_Text

