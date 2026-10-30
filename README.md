SMS Spam Detection Using Machine Learning

<p align="center">
  A Machine Learning approach to automatically identify and classify SMS messages as Spam or Ham.
</p>
1. Project Overview

SMS (Short Message Service) is widely used for personal and professional communication. However, unwanted promotional messages, fraudulent offers, and suspicious messages are common problems.

This project aims to develop a Machine Learning model that automatically identifies whether an SMS message is Spam (unwanted message) or Ham (legitimate message).

The system uses Natural Language Processing (NLP) techniques to understand text messages and a Multinomial Naive Bayes classifier to make predictions.

2. Project Objectives

- Understand and preprocess SMS text data.
- Convert text messages into numerical features.
- Train a Machine Learning classification model.
- Evaluate the model's performance.
- Predict whether a new SMS message is Spam or Ham.

3. Dataset

Dataset Name: UCI SMS Spam Collection

Source: UCI Machine Learning Repository

Dataset Link: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

The dataset contains SMS messages labeled into two categories:

- Ham: Legitimate messages.
- Spam: Unwanted or promotional messages.

4. Technologies and Libraries

Technology| Purpose
Python| Programming language
Pandas| Data handling and analysis
NumPy| Numerical operations
Matplotlib| Data visualization
Seaborn| Statistical visualization
Scikit-learn| Machine Learning
TF-IDF| Text feature extraction

5. Machine Learning Algorithm

TF-IDF (Term Frequency–Inverse Document Frequency)

TF-IDF converts text messages into numerical features so that a Machine Learning algorithm can process them.

Multinomial Naive Bayes

This classification algorithm learns from the training messages and predicts whether a new message belongs to the Spam or Ham category.

6. Project Workflow

1. Import the required Python libraries.
2. Load the SMS Spam Collection dataset.
3. Explore and understand the dataset.
4. Preprocess the SMS text data.
5. Convert text into numerical features using TF-IDF.
6. Split the dataset into training and testing sets.
7. Train the Multinomial Naive Bayes classifier.
8. Evaluate the trained model.
9. Visualize the model performance.
10. Test the model with new SMS messages.

7. Model Evaluation

The model is evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

Model Accuracy: Approximately 98.41%

8. Project Structure

SMS-Spam-Detection-ML/
│
├── Spam_Ham_Classification.ipynb
└── README.md

9. How to Run the Project

1. Download or clone this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Run the notebook cells in sequence.
4. Follow the instructions to train and test the model.

10. Expected Output

The trained model accepts an SMS message as input and predicts one of the following:

- Spam
- Ham

This helps demonstrate how Machine Learning can be applied to real-world text classification problems.

11. Conclusion

This project demonstrates the practical application of Machine Learning and Natural Language Processing for SMS spam detection.

By combining TF-IDF feature extraction with the Multinomial Naive Bayes algorithm, the model learns to distinguish unwanted messages from legitimate messages.

This project provided practical experience in data preprocessing, feature extraction, model training, evaluation, and prediction.

---

Developed as a Beginner-Level Machine Learning Project.
