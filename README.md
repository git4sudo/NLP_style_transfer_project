# Text Style Transfer: Informal to Formal

This project focuses on implementing and comparing different approaches to text style transfer, specifically converting informal text to formal text using Natural Language Processing (NLP) techniques.

## Project Overview

The goal of this project is to explore and evaluate various methods for transforming the style of text from informal to formal while preserving its original content. We utilize and compare different models and techniques, including:

1. Sequence-to-Sequence (Seq2Seq) model
2. T5 (Text-to-Text Transfer Transformer) model
3. GPT-2 model
4. Hugging Face's pre-trained model for style transfer

## Dataset

We use the GYAFC (Grammarly's Yahoo Answers Formality Corpus) dataset, which contains pairs of informal and formal sentences. The dataset is split into two domains:

- Entertainment & Music
- Family & Relationships

## Models and Implementations

### 1. Sequence-to-Sequence (Seq2Seq) Model
- Implemented using TensorFlow/Keras
- Encoder-Decoder architecture with LSTM layers

### 2. T5 Model
- Fine-tuned on our dataset
- Used for both training and inference

### 3. GPT-2 Model
- Fine-tuned on our dataset
- Explored its capabilities in style transfer tasks

### 4. Hugging Face Pre-trained Model
- Utilized the `prithivida/informal_to_formal_styletransfer` model
- Used for comparison and baseline performance

## Evaluation Metrics

We evaluate the performance of our models using two primary metrics:

1. BLEU (Bilingual Evaluation Understudy) Score
2. TER (Translation Edit Rate) Score

These metrics help us assess the quality and accuracy of the style transfer results.

## Future Work

- Explore more advanced architectures and techniques
- Incorporate additional datasets for improved generalization
- Investigate bi-directional style transfer (formal to informal as well)

## Acknowledgments

- GYAFC Corpus for providing the dataset
- Hugging Face for pre-trained models and libraries
