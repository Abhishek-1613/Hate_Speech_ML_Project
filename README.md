# Hate Speech Detection for Social Media (Machine Learning Project)

## Overview
This project involves detecting hate speech, offensive speech, or normal speech from tweets and comments on social media platforms. Various machine learning models are implemented and compared to identify the most effective model for this task.
## Libraries Used: Pandas, Numpy, Sklearn, Scikitplot, Seaborn, Matplotlib

## Features
- Implementation of Logistic Regression, Random Forest, Decision Tree, and SVM models.
- Utilization of TF-IDF Vectorizer for text processing and checking models with/without oversampling.
- Comparison of model performance to select the optimal model.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/hate-speech-detection.git
    cd hate-speech-detection
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare the dataset (e.g., Kaggle dataset) and place it in the `data` folder.
2. Run the model training script:
    Using Jupyter Notebook this project can be ran easily with all the libraries I mentioned above installed.
3. Evaluate the models and identify the best-performing model:
    At the end of all the Models the results were shown and we compared them alongwith their AUC-ROC curves for final decision.

## Results
The project demonstrates the comparison of different machine learning models for hate speech detection, with detailed performance metrics for each model and for our Dataset SVM and Random forest were the best.
