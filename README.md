# Spam Email Classification Challenge

This project is part of a boot camp challenge to develop a supervised machine learning model that classifies emails as spam or not spam using a provided dataset.

# Project Overview

The goal is to train and evaluate two different classification models:

- **Logistic Regression**
- **Random Forest Classifier**
The models are compared based on their accuracy in detecting spam emails.

# Dataset

- **Source:** UCI Machine Learning Repository
- **Data URL:** Spam Dataset
- **Features:** Word frequencies, character counts, and capital letter usage.
- **Target Variable:**
    0 = Not Spam
    1 = Spam

# Process

1. **Data Preparation**
    - Load and inspect the dataset.
    - Split the data into features (X) and labels (y).
    - Check class balance.

2. **Data Preprocessing**
    - Split the data into training (80%) and testing (20%) sets.
    - Scale features using StandardScaler.

3. **Model Training & Evaluation**
    - Train Logistic Regression and Random Forest models.
    - Evaluate their performance using accuracy scores.

# Results

    - Logistic Regression Accuracy: 92.73%
    - Random Forest Accuracy: 95.87%

**Conclusion:** The Random Forest Classifier outperformed Logistic Regression, achieving higher accuracy in detecting spam emails.

# Technologies Used

    - Python
    - Pandas
    - Scikit-learn
    - Jupyter Notebook

# How to Run the Project

1. Clone this repository:
    ``git clone <repo-url>``

2. Install dependencies:
    ``pip install pandas scikit-learn``

3. Open spam_detector.ipynb in Jupyter Notebook and run the cells.
