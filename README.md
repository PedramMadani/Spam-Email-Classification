# Email Spam Classification Project

## Project Overview
This project aims to classify emails as spam or not spam using the SMS Spam Collection dataset from Kaggle.

## Methods Used
- Text preprocessing (tokenization, removing stop words, vectorization)
- Logistic Regression with L1 regularization

## Technologies
- Python
- Pandas, scikit-learn, matplotlib

## Project Structure
- `data/`: Folder containing the dataset.
- `notebooks/`: Jupyter notebooks with detailed analysis.

## Data

The dataset used in this project is the "SMS Spam Collection" dataset from Kaggle. 

## Model

The model used is a logistic regression model with L1 regularization. The model was chosen for its simplicity and effectiveness in binary classification tasks.

## Evaluation Metrics

The model was evaluated using the following metrics:

- **Accuracy**: The proportion of correctly predicted instances.
- **Precision**: The proportion of positive predictions that were actually correct.
- **Recall**: The proportion of actual positives that were correctly predicted.
- **F1 Score**: The harmonic mean of precision and recall.

## Results

The model's performance on the test set was as follows:

- **Accuracy**: 0.9779
- **Precision**: 0.9840
- **Recall**: 0.8447
- **F1 Score**: 0.9091

## Dependencies

The project uses the following dependencies:

- `pandas`
- `matplotlib`
- `scikit-learn`

## Instructions

1. Clone the repository.
2. Install the dependencies using `pip install -r requirements.txt`.
3. Open and run the Jupyter Notebook `email_spam_classification.ipynb`.

## License

This project is licensed under the MIT License.