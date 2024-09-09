# 🎥 Movie Genre Classifier

This project is part of a series where I explore AI and machine learning techniques. Here, I build a **Movie Genre Classifier** using the **Multinomial Naive Bayes** algorithm to predict genres based on text data.

## 📚 Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

This project aims to classify movies into various genres based on their descriptions and other textual features. Using the Multinomial Naive Bayes algorithm, we can achieve an accuracy of over 91% on our test dataset.

## Dataset

The dataset used in this project is sourced from Kaggle and contains various features related to movies, including their descriptions and genres.

## Model

The Multinomial Naive Bayes model was selected for this project as it performs well on text classification problems. Various hyperparameters, such as `alpha`, were tuned to find the best model.

### Key Steps:
1. Data Preprocessing and Cleaning
2. Feature Extraction using TF-IDF
3. Model Training and Evaluation
4. Hyperparameter Tuning
5. Model Evaluation using Confusion Matrix

## Results

- The model achieved an **accuracy of 91.34%** with `alpha=0.1`.
- Confusion Matrix Insights:
  - The model performs well on genres like "Drama" and "Thriller".
  - Some misclassifications exist between similar genres like "Action" and "Thriller".

![Confusion Matrix](path-to-image/confusion_matrix.png)

## Installation

To run this project, you will need to install the necessary dependencies. You can do this by running:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/Adeel-Farooq-Khan/movie-genre-classifier.git
    cd movie-genre-classifier
    ```
   
2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Movies\ Genre\ Movies Genre Classifier.ipynb
    ```

3. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

