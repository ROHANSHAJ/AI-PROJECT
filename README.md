## IBM: AI101
## Artificial Intelligence - Group 2    
### SENTIMENT ANALYSIS  

--------------------------------------
## PROJECT LINK
https://drive.google.com/file/d/19yAguvwdFVJv9GEz8b-Q3O280pzWMfLS/view?usp=sharing  

---------------------------------------------------------------------------------
## DATASET LINK 
https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment/data  

----------------------------------------------------------
## OVERVIEW

This project demonstrates how to perform sentiment analysis using a combination of BERT (Bidirectional Encoder Representations from Transformers) and a GRU (Gated Recurrent Unit) neural network. The code processes textual data, preprocesses it, trains a model, and evaluates its performance.

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Preprocessing](#preprocessing)
4. [Training](#training)
5. [Evaluation](#evaluation)
6. [Usage](#usage)
7. [Dependencies](#dependencies)
8. [Acknowledgments](#acknowledgments)

## Introduction

Sentiment analysis, also known as opinion mining, aims to determine the sentiment expressed in text data, such as positive, negative, or neutral. This project uses BERT, a powerful pre-trained transformer model, in combination with a GRU layer for sentiment analysis.

## Installation

To run this project, you need to install the required packages. Run the following commands in your Python environment:

bash
pip install emoji
pip install transformers
pip install torch
pip install nltk
pip install pydot
pip install graphviz
pip install tensorflow
pip install tensorflow==2.14.0


## Preprocessing

Before training the model, data preprocessing is essential. In this project, data preprocessing involves text cleaning, stemming, and tokenization. The code handles data preprocessing and prepares the data for training.

## Training

The training process involves training the sentiment analysis model using the provided data. The code includes the definition of the model architecture, training parameters, and training loops.

## Evaluation

After training, the model's performance is evaluated using a validation dataset. The code provides evaluation metrics and assesses the model's accuracy.

## Usage

To run the code and use the sentiment analysis model, follow these steps:

1. Install the required packages as mentioned in the "Installation" section.
2. Execute the code snippets provided in the "Training" section to train the model.
3. After training, use the code snippets in the "Evaluation" section to evaluate the model.
4. For sentiment analysis predictions on new text data, you can adapt the model for your specific use case.

## Dependencies

The project relies on several Python libraries and packages, including but not limited to:

- emoji
- transformers
- torch
- nltk
- pydot
- graphviz
- tensorflow

Ensure you have these dependencies installed to run the project.


## Acknowledgments

We would like to acknowledge the open-source libraries and tools that made this project possible, including BERT, Transformers, and other machine learning libraries.

If you have any questions or need further assistance, please feel free to reach out.

Happy sentiment analysis!

This README file provides a detailed guide on how to run your code, from installation to usage.
----------------------------------------------------------
## CONCLUSION  
This project aims to analyze sentiment on Twitter related to various airlines using BERT (Bidirectional Encoder Representations from Transformers) as a state-of-the-art natural language processing model. It helps you understand how the public perceives different airlines by classifying tweets into positive, negative, or neutral sentiments.    
---------------------------------------------------------------------------------
## NOTE  
IF IN COLAB NOTEBOOK, CLICK ON THE FILE ICON  > ON THE TOP LEFT OF THE NOTEBOOK AND CLICK ON FILES. LOCATE THE CSV FILE FOR SENTIMENT ANALYSIS.  

CHANGE HARDWARE ACCELERATOR TO T4 GPU IN COLAB'S RUNTIME TYPE SETTINGS.  


---------------------------------------------------------------------
  
##THANK YOU

--------------------------------------------------------------


