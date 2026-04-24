# SentimentScope

> **Udacity AI Programming with Python Nanodegree — Project**

## Project Overview

SentimentScope is a sentiment analysis project built as part of the Udacity AI Programming with Python Nanodegree. The goal is to design, train, and evaluate a transformer-based model that classifies user reviews as positive or negative using the IMDB dataset.

## Background

Imagine you're a Machine Learning Engineer at **CineScope**, an entertainment company dedicated to helping audiences discover movies and shows they'll love. CineScope aims to enhance its recommendation system by understanding user sentiment (positive or negative) about the content they engage with, enabling more accurate and personalized suggestions.

### The Challenge

The technical challenge lies in building and fine-tuning a transformer-based model capable of performing sentiment analysis on large-scale text data, specifically user reviews from IMDB. This involves designing a model architecture that can process nuanced linguistic patterns, training it effectively for classification tasks, and ensuring it achieves a high degree of accuracy. The insights derived will play a crucial role in refining the personalization algorithms, directly impacting user satisfaction and engagement.

## Core Components

| Component | Description |
|---|---|
| **Data Preparation** | Cleaning, tokenizing, and splitting the IMDB dataset into training, validation, and test sets |
| **Transformer Model Architecture** | Customizing a transformer-based neural network for sentiment analysis, including tweaks for classification tasks |
| **Data Loading and Processing** | Implementing a PyTorch `DataLoader` to efficiently feed data into the model during training and evaluation |
| **Training and Validation Framework** | Developing functions for model training and validation, including loss calculation and optimization |
| **Testing and Evaluation** | Creating a robust evaluation function to test the model's accuracy on unseen data |

## Dataset

[IMDB Movie Reviews Dataset](https://huggingface.co/datasets/imdb) — 50,000 labeled movie reviews (25k train / 25k test), balanced between positive and negative sentiment.

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers / Datasets
- Jupyter Notebook
