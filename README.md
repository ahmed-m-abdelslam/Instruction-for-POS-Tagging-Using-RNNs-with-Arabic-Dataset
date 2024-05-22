Instruction for POS Tagging Using RNNs with Arabic Dataset

Dataset: The dataset provided is named "Assignment 2 - Arabic POS.conllu". It contains labeled data for Arabic text with Part-of-Speech (POS) tags in CoNLL-U format.

Objective: objective is to perform Part-of-Speech (POS) tagging on Arabic text using Recurrent Neural Networks (RNNs). Specifically, you will use the Universal POS (UPOS) tags for tagging. UPOS is a standardized set of POS tags that aims to cover all languages.

Evaluation metric: Accuracy

Instructions:

Data Preprocessing:

Load the provided dataset "Assignment 2 - Arabic POS.conllu".useing pyconll library
Preprocess the data as necessary, including tokenization
Model Building:

Design an RNN-based model architecture suitable for POS tagging. May consider using recurrent layers such as (LSTM) or (GRU).
Define the input and output layers of the model. The input layer should accept sequences of tokens, and the output layer should produce the predicted UPOS tags for each token.
Training:

Evaluation:
