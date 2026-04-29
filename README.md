# 🍎 Food Classification

A deep learning project for identifying **fruit type and quality** using image classification.

## Overview

This project trains a convolutional neural network (CNN) to classify fruits by both their **type** (e.g., apple, banana, orange) and **quality** (e.g., fresh vs. rotten). The full pipeline — from data loading and preprocessing to model training and evaluation — is implemented in a single Jupyter Notebook.

## Repository Structure

```
Food-Classification/
├── food_classification.ipynb   # Main notebook: data prep, model training, evaluation
└── README.md
```

## Getting Started

### Prerequisites

```bash
pip install tensorflow keras numpy matplotlib scikit-learn jupyter
```

### Running the Notebook

```bash
git clone https://github.com/ianliu1119/Food-Classification.git
cd Food-Classification
jupyter notebook food_classification.ipynb
```

## Methodology

- **Model**: Convolutional Neural Network (CNN) / Transfer Learning
- **Task**: Multi-class image classification (fruit type + quality)
- **Framework**: TensorFlow / Keras
- **Environment**: Google Colab / Jupyter Notebook

## Dataset

The model is trained on a labeled dataset of fruit images organized by type and quality. Images are preprocessed with resizing, normalization, and data augmentation to improve generalization.

> If using Kaggle datasets, configure your Kaggle API credentials before running the notebook.

## Results

Training accuracy, validation accuracy, and loss curves are visualized within the notebook, along with a confusion matrix and per-class performance metrics.
