﻿# LLM Reasoning Evaluator

A Python-based  for evaluating and comparing Language Model reasoning capabilities using CommonsenseQA and Winograd Schema Challenge datasets.

## Features

- Support for both causal and sequence-to-sequence language models
- Built-in evaluation metrics (BLEU, ROUGE, F1)
- Visualization tools for model performance
- Flexible training and prediction interfaces
- Handles multiple datasets (CommonsenseQA and Winograd Schema Challenge)

## Dependencies


```bash
pip install transformers # Hugging Face Transformers library for LLM models
pip install datasets # Hugging Face Datasets library for loading benchmark datasets
pip install nltk # Natural Language Toolkit for BLEU score
pip install rouge-score # For ROUGE metrics calculation
pip install scikit-learn # For F1 score and other metrics
pip install matplotlib # For visualization 

```


The framework provides several evaluation metrics:
- BLEU Score
- ROUGE-1 Score
- ROUGE-L Score
- F1 Score

## Supported Models

- Causal Language Models (e.g., GPT-2)
- Sequence-to-Sequence Models (e.g., T5)



## Example Datasets

The framework includes support for:
1. CommonsenseQA
2. Winograd Schema Challenge (WSC)


