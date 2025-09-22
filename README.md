#  Transformers 

## Project Overview
This repository contains the implementation of Lab 5 focusing on transformer models, including BERT embeddings, fine-tuning for classification, and autoregressive text generation.

## 📋 Project Tasks

### Text Similarity with BERT
- **Objective**: Compute cosine similarity between BERT embeddings
- **Input**: `data/task1/sentences.csv`
- **Output**: `similarity.csv`
- **Key Features**: Batch processing, GPU acceleration, similarity matrix generation

###  Fine-Tuning RoBERTa for Classification
- **Objective**: Binary text classification with F1-score > 0.77
- **Input**: `data/task2/train/` and `data/task2/test/`
- **Output**: `submission.csv`
- **Model**: RoBERTa-base with custom classification head
- **Training**: Early stopping, learning rate scheduling, stratified validation

###  Autoregressive BERT Extension
- **Objective**: Text generation using BERT with causal masking
- **Features**: Recursive generation, automatic stopping conditions
- **Examples**: "The capital of France is Paris."

## 🚀 Quick Start

### Prerequisites
```bash
pip install transformers torch scikit-learn datasets matplotlib
