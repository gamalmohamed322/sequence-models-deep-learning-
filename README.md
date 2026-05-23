# Sequence Models for IMDb Sentiment Classification

## Overview
This project compares several deep learning sequence models for sentiment classification on the IMDb movie review dataset. The goal is to classify movie reviews as positive or negative using different neural network architectures.

## Models Implemented
- Simple RNN
- LSTM
- GRU
- Transformer-based model

## Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Workflow
1. Load and preprocess the IMDb review dataset
2. Prepare text sequences for model training
3. Build and train multiple sequence models
4. Evaluate model performance
5. Compare accuracy, training behavior, and model strengths

## Results
The GRU model achieved the highest test accuracy, while the Transformer model trained faster and still performed competitively. The Simple RNN performed the weakest because it struggles with long-range dependencies in text.

## Key Learnings
- RNNs are useful for sequence data but can struggle with long text dependencies.
- LSTM and GRU models handle sequential information better than Simple RNNs.
- Transformer-based models can train efficiently and capture important word relationships.
- Comparing multiple models helps identify the best architecture for a specific NLP task.

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/gamalmohamed322/sequence-models-deep-learning-.git
