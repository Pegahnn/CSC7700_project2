# CSC7700_project2
This project explores and compares the performance of Recurrent Neural Networks (RNN), Long Short-Term Memory Networks (LSTM), and Transformer-based models on a text generation task. Each model is trained using tokenized data with a Byte Pair Encoding (BPE) tokenizer built using SentencePiece.
The dataset consists of short text sequences extracted from public domain literature, specifically, 
Project Gutenberg.
📁 Notebooks
RNN.ipynb:
Performs tokenization using SentencePiece

Trains and evaluates a basic RNN model

Generates text samples

➤ LSTM.ipynb and Transformer.ipynb:
Assume tokenized data already exists

Load data from .pt files

Train and evaluate LSTM/Transformer models

Generate sample outputs
Install Dependencies
Create a virtual environment (optional) and install dependencies:
pip install torch sentencepiece matplotlib nltk gdown
