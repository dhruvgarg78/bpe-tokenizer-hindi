# BPE Tokenizer for Hindi

This repository contains a Byte Pair Encoding (BPE) tokenizer for Hindi text. The goal of this project is to implement and optimize the BPE algorithm to create an efficient tokenizer that can handle Hindi text data.

## Compression and Vocabulary

- **Compression Ratio**: 9.24x
- **Vocabulary Size**: 4500 tokens

## Files

1. **`BPE_Training.ipynb`**: The Jupyter notebook for training the BPE model on Hindi text.
2. **`hindilit.txt`**: The raw Hindi text data used for training.

## Overview

Byte Pair Encoding (BPE) is a popular tokenization algorithm used for subword tokenization in NLP. The BPE method splits words into subword units by iteratively merging the most frequent pairs of characters or subwords, allowing the model to efficiently represent rare words.

In this project, we used the BPE algorithm to train a tokenizer specifically for Hindi text, achieving a compression ratio of 9.24x and a vocabulary size of 4500 tokens.

## How to Use

### Step 1: Clone the Repository
```bash
git clone https://github.com/dhruvgarg78/bpe-tokenizer-hindi.git
cd bpe-tokenizer-hindi
