# Language Modeling with N-gram

This project implements N-gram language models in Python for analyzing word sequences and estimating their probabilities from a given corpus.

## Overview

The project explores unigram, bigram, trigram, and four-gram models and demonstrates how N-gram frequencies can be used to estimate the probability of word sequences and sentences.

## Features

- Count unigram, bigram, trigram, and four-gram occurrences
- Find the most frequent N-grams in the corpus
- Identify words that can follow a given word
- Calculate Maximum Likelihood Estimation (MLE) probabilities
- Calculate the probability of individual N-grams
- Estimate sentence probability using a bigram model
- Apply Add-1 (Laplace) smoothing for unseen N-grams

## Example

The project calculates the probability of the sentence:

`how do you do`

using a bigram language model with Add-1 smoothing.

## Technologies

- Python
- NLTK
- Pandas
- NumPy

## Purpose

This project was developed as part of a Natural Language Processing course to demonstrate N-gram language modeling, probability estimation, frequency analysis, and smoothing techniques.
