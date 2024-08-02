# Email Spam Detection using Machine Learning

This project implements an email spam detection model using machine learning techniques. The model is trained on a dataset of emails labeled as either "spam" or "ham" (non-spam).

## Dataset

The dataset used in this project is located in the `input/mail_data.csv` file. It contains a collection of emails labeled as spam or ham.

## Model

The model used in this project is a Logistic Regression model. The features used to train the model are extracted using a TF-IDF vectorizer.

## Usage

To run the project, follow these steps:

1. Install the required libraries:

```python
pip install numpy pandas scikit-learn
```

2. Run the Jupyter Notebook file `model.ipynb`.

## Results

The model achieves an accuracy of approximately **97%** on the test set.
