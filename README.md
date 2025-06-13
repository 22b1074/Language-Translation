# English to Hindi Translation

## Overview
This project translates English sentences to Hindi using a custom Transformer model with self-attention.

## Features
- **Custom Tokenizer:** Trained `ByteLevelBPETokenizer` from HuggingFace on English and Hindi data.
- **Transformer from Scratch:** Implemented encoder, decoder, and multi-head attention manually using PyTorch.
- **Training Method:** Used teacher forcing on parallel sentence pairs to help the model learn better.
- **Evaluation:** Tracks accuracy and loss on both training and validation sets, and saves the best model (`best_model.pth`).

## Dataset
- Used the [IIT Bombay English-Hindi Parallel Corpus](https://huggingface.co/datasets/cfilt/iitb-english-hindi) from HuggingFace Datasets.

## Output
- Trained model weights: `best_model.pth`

