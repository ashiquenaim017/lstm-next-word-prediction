# LSTM-Based Next Word Prediction Using PyTorch

## Overview

This project implements a next-word prediction model using a Long Short-Term Memory (LSTM) neural network in PyTorch. It demonstrates how text can be tokenized, converted into numerical sequences, and used to train a neural network for language modeling.

## Objectives

- Preprocess text using NLTK tokenization.
- Build a vocabulary and convert words into numerical indices.
- Generate and pad training sequences.
- Build and train an LSTM-based neural network.
- Predict the next word from an input sequence.
- Generate text iteratively using model predictions.

## Technologies Used

- Python
- PyTorch
- NumPy
- NLTK
- Jupyter Notebook

## Model Architecture

The model consists of:

1. **Embedding Layer:** Converts word indices into dense vector representations.
2. **LSTM Layer:** Learns sequential patterns in the input text.
3. **Fully Connected Layer:** Produces scores for possible next words.

The model is trained using the Adam optimizer and Cross-Entropy Loss.

## Dataset

The current implementation uses a short story embedded directly in the notebook as its training corpus. The model learns word-transition patterns from this text.

## How to Run

1. Clone this repository.
2. Install the required dependencies.
3. Open `LSTM_Project.ipynb` in Jupyter Notebook or Google Colab.
4. Run the notebook cells in order.

Install dependencies:

```bash
pip install torch numpy nltk
```

## Evaluation

The notebook includes a training loop and an accuracy calculation on the training dataset. A separate held-out test dataset has not been implemented, so the reported accuracy should not be interpreted as generalization performance.

## Future Improvements

- Use a larger text corpus.
- Create separate training, validation, and test datasets.
- Add loss and evaluation plots.
- Improve text preprocessing and sequence handling.
- Experiment with model hyperparameters and text-generation strategies.

## Learning Outcomes

This project demonstrates practical experience with sequence modeling, natural language processing, text preprocessing, PyTorch model development, and neural network training.
