# X-Sentiment-Analysis

A complete Twitter sentiment analysis system built using the **Sentiment140 dataset** (1.6M tweets).  
This project demonstrates full NLP preprocessing, feature extraction, machine learning model training, and sentiment prediction.

---

## Table of Contents

- [About](#about)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)
- [Run / Usage](#run--usage)
- [How the Model Works (high level)](#how-the-model-works-high-level)
- [Retrain / Rebuild](#retrain--rebuild)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

---

## About

This repository contains a **Sentiment Analysis** model that classifies tweets into **Positive**, **Negative**, or **Neutral** using machine learning.  
All steps—data cleaning, preprocessing, TF-IDF vectorization, model training, and evaluation—are implemented in a Jupyter notebook (`sentiment_model.ipynb`).

The project uses the **Sentiment140 Kaggle dataset**, widely used for Twitter sentiment research.

---

## Features

- Full NLP preprocessing pipeline  
- Machine learning models (Logistic Regression, Naive Bayes, SVM, Random Forest)  
- TF-IDF and n-gram based feature engineering  
- Visualizations & evaluation metrics  
- Predict sentiment for custom input text  
- Easy to retrain / modify  

---

## Repository Structure

X-Sentiment-Analysis/
├─ sentiment_model.ipynb # Main notebook: cleaning → vectorizing → training
├─ dataset/ # Dataset (optional)
├─ requirements.txt # Dependencies
├─ models/ # Trained models (optional)
└─ README.md
