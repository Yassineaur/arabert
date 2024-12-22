# **Lab Project on Fine-Tuning Language Models**  
## *Advanced Natural Language Processing Course*  
**University Year:** 2024/2025  

---

# Project Goals

## Optimizing the Target Model
- Adapt a pre-trained BERT model specifically for the **Arabic Sentiment Tweets** dataset.
- Assess model performance on the test set using evaluation metrics from **TorchMetrics**.

## Introducing Multi-Head Differential Attention
- Design and implement a custom **multi-head attention** mechanism based on **differential attention** principles.
- Seamlessly integrate this mechanism into the fine-tuned BERT architecture.

## Exploring Hybrid Attention Approaches
- Partially replace **25%-50%** of the encoder and/or decoder layers’ multi-head attention with the new differential attention mechanism.
- Train and evaluate the performance of each modified configuration.

---

# Dataset  
**Name:** Arabic Sentiment Tweets Dataset  
- **Task:** Text Classification  
- **Dataset Link:** [Mendeley Data](https://data.mendeley.com/datasets/57zpx667y9/2)  

---

# Pre-trained Model  
**Model:** BERT  
- **Pre-trained Version:** [BERT-Base-ArabertV2](https://huggingface.co/aubmindlab/bert-base-arabertv2)  

---

# Setup Instructions

## Prerequisites
To run this project, ensure you have the following dependencies installed:

- Python 3.x
- PyTorch (preferably version 1.10+)
- Transformers library from Hugging Face
- TorchMetrics
- Datasets from Hugging Face or other relevant data sources
