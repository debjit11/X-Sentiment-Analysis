# X-Sentiment-Analysis 

**A simple, easy-to-run Twitter (X) sentiment analysis system built using the Sentiment140 dataset.**

---

## Table of Contents

* [About](#about)
* [Features](#features)
* [Repository Structure](#repository-structure)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Dataset](#dataset)
* [Run / Usage](#run--usage)

---

## About

This repository contains a sentiment analysis pipeline for tweets on the X (formerly Twitter) platform.  
It uses the **Sentiment140** dataset containing **1.6M+ labeled tweets**.  

The project includes:

- A complete Jupyter notebook demonstrating preprocessing, feature extraction, model training, and evaluation.  
- Saved model/vectorizer files for quick prediction.  
- Optional script to classify custom tweets.

---

## Features

* End-to-end NLP pipeline: cleaning, tokenization, stop-word removal, stemming/lemmatization  
* TF-IDF vectorization with optional n-grams  
* Machine-learning models such as Logistic Regression / SVM / Naive Bayes (based on your repo setup)  
* Confusion matrix & evaluation metrics  
* Predict sentiment for custom user-input text  
* Easy retraining and extension  

---

## Repository Structure

X-Sentiment-Analysis/
* ├─ .gitignore
* ├─ README.md # Documentation
* ├─ x_analysis.ipynb # Notebook: full sentiment analysis pipeline
* ├─ vectorizer.pkl # Saved vectorizer (TF-IDF)
* ├─ logistic.pkl # Trained model for sentiment prediction
*  ─ requirements.txt # Python dependencies
* ├─ dataset/ # (optional) Place raw/processed data here
* └─ app.py (optional) # Script for real-time sentiment prediction


> Modify the names above if your repo structure differs.

---

## Prerequisites

* Python 3.13
* Git
* Jupyter Notebook / JupyterLab (optional)

---

## Installation

```bash
# 1. Clone the repo
git clone https://github.com/debjit11/X-Sentiment-Analysis.git
cd X-Sentiment-Analysis

# 2. Create and activate a virtual environment
# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate

# Windows (PowerShell)
python -m venv .venv
.\.venv\Scripts\Activate.ps1


# 3. Install dependencies
pip install --upgrade pip
pip install -r requirements.txt

```
## Dataset

This project uses the Sentiment140 dataset from Kaggle:
https://www.kaggle.com/datasets/kazanova/sentiment140

Dataset Info:

1,600,000 tweets

Labeled as:

* 0 → Negative

* 2 → Neutral

* 4 → Positive

## Run / Usage

jupyter notebook x_analysis.ipynb

