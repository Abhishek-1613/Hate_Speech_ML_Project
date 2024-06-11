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
    git clone https://github.com/Abhishek-1613/Hate_Speech_ML_Project.git
    cd ML_Hate_Speech_Detection_Project
    ```
2. Install the required packages:
    ```bash
    pip install pandas numpy sklearn scikitplot matplotlib seaborn
    ```

## Usage
1. Prepare the dataset (e.g., the Kaggle dataset) and place it in the `data` folder.
2. Run the model training script:
    Using Jupyter Notebook, this project can be run easily with all the libraries I mentioned above installed.
3. Evaluate the models and identify the best-performing model:
    At the end of all the Models, the results were shown, and we compared them along with their AUC-ROC curves for the final decision.

## Results
The project compares different machine learning models for hate speech detection, with detailed performance metrics for each model. For our Dataset, SVM and Random Forest were the best.

## Note
You can also check a similar project in the repository named "ALternate_ML_IR_Project," which I did as an assignment for a company.
