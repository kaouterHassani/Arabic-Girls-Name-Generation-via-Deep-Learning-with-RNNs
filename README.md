# Arabic-Girls-Name-Generation-via-Deep-Learning-with-RNNs
This project focuses on generating Arabic girls' names using a character-level Recurrent Neural Network (RNN). The model is trained on a dataset of Arabic girls' names and can generate new names based on learned patterns.

## Table Of Contents
* [Overview](#Overview)
* [DataSet](#DataSet)
* [Model](#Model)
* [Installation](#Installation)
* [Results](#Results)

## Overview
This project utilizes a character-level Recurrent Neural Network (RNN) to generate unique Arabic girls' names. By learning patterns from an existing dataset of names, the model predicts and generates new names in Arabic.

## DataSet: 
This dataset contains a comprehensive collection of Arabic girls' names, which I compiled from various online sources, it is a text file named `Arabic_Girls_names.txt` . It includes over 500 unique names, providing a rich resource for generating new names using the RNN .

## Model
The model used in this project is a Character-Level Recurrent Neural Network (RNN). It processes names as sequences of characters and learns to generate plausible names based on the structure of the training data.

### Key Features
 * RNN Architecture : A simple Reccurent Neural Network architecture .
 * Character Embedding: Converts each character into an embedding vector.
 * Loss Function: Cross-entropy loss for next character prediction.
 * Optimization: The model is trained using gradient descent with an Adam optimizer.

## Installation
 * Python 3.8.10
 * Numpy

## Results 
After training, the RNN generates names that resemble those in the dataset. Some examples of generated names include:
* `Hafa`
* `Haafiya`
* `Mika`
* `Zoraa`
* `Mayyka`
* `Meha`
* `Gaadiya`
* `Zunah`
* `Haadiya`

  
