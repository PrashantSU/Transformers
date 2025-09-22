# Transformers Lab: BERT & RoBERTa Implementation

## Project Description
This project demonstrates practical applications of transformer models including text similarity analysis, text classification, and autoregressive text generation using BERT and RoBERTa.

## Features
- **Text Similarity**: Compute semantic similarity using BERT embeddings
- **Text Classification**: Fine-tune RoBERTa for sentiment analysis
- **Text Generation**: Autoregressive text completion with BERT

## Models Used
- BERT-base for embeddings and generation
- RoBERTa-base for classification
- Custom training pipelines and evaluation

## Technical Highlights
- GPU-accelerated training and inference
- Early stopping and learning rate scheduling
- Batch processing for efficiency
- Custom dataset handling

## Results
- Achieved >0.79 F1-score on classification task
- Successful text generation with coherent outputs
- Efficient similarity computation for text pairs

## Quick Start
```python
# Install dependencies
pip install transformers torch datasets

# Run the main notebook to see all implementations
