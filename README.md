# Parlez-vous-Francais

I always wondered how translation services like Google Translate actually worked. This project is an introductory effort to understand the concepts behind it! This is Project-4 of Udacity's Deep Learning Foundations Nanodegree.

This network employs the seq2seq architecture, and has been currently trained on a very small corpus of english-french translations.
This same network **can be trained for any language**, and the translation service can be made more accurate by using a bigger dataset for training.

## Dependencies
1. Jupyter Notebook
2. Numpy
3. Tensorflow


Install all requirements using:
``pip install``

## A Translation Example
English: ``he saw a old yellow truck.``

French: ``il a vu un vieux camion jaune.``

## Please Note
I have used FloydHub for training and validating my model. The training and validation accuracy have reached upto 97%. (Maybe overfitting a little?)
