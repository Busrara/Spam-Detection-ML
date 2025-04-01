# Spam Classification with ML

This project is  prepared to classify SMS messages as either **ham** (legitimate) or **spam** using various classification models. The project implements **Random Forest** and **Naive Bayes** classifiers,and also data preprocessing techniques like TF-IDF vectorization and SMOTE for class imbalance.

---

## 📋 **Project Overview**

In this project, we aim to predict whether a given SMS message is spam or not. The main steps are:
- Data preprocessing: cleaning and tokenizing text data.
- Feature extraction: transforming text data into numerical format by TF-IDF.
- Model training: applying machine learning classifiers to the dataset.
- Model evaluation: assessing performance using accuracy, precision, recall, and F1-score metrics.

---
## 🛠 **Installation**
  Install necessary libraries if you are using Google Colab.

📚 **Libraries Used**

The project needs the following Python libraries:

- pandas: For data handling and manipulation.
- numpy: For numerical operations.
- scikit-learn: For machine learning algorithms.
- imblearn: For the SMOTE oversampling technique.
- matplotlib & seaborn: For data visualization.
- nltk: For text processing and natural language tasks.

📊 **Dataset**

The dataset used in this project contains SMS messages labeled in two groups:

- ham: Legitimate messages.
- spam: Spam messages.

It’s a pre-processed dataset so it is already ready for use with machine learning models.

# How It Works 

### 1. Data Preprocessing
- Clean the raw text data.
- Tokenize the messages and remove unwanted characters.
- Convert the text data into numerical features using TF-IDF vectorization.

### 2. Handling Class Imbalance
We use SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset by generating synthetic samples of the minority class (spam).

### 3. Model Training
- Random Forest Classifier: A powerful ensemble learning method.
-  Naive Bayes Classifier: A probabilistic classifier based on Bayes' theorem.

### 4. Model Evaluation
- Accuracy, precision, recall, and F1-score are used to evaluate both models.
- Confusion matrices visualize the model’s performance in classifying spam and ham messages.

📈 **Model Performance**

### Random Forest Confusion Matrix
- **Accuracy**: 99.41
- **True Positive (TP)**: 1435
- **False Positive (FP)**: 3
- **False Negative (FN)**: 14
- **True Negative (TN)**: 1443

### Naive Bayes Confusion Matrix
- **Accuracy**: 98.69%
- **True Positive (TP)**: 1435
- **False Positive (FP)**: 22
- **False Negative (FN)**: 16
- **True Negative (TN)**: 1422

To have a further understanding of the project, you can read my Medium writing: https://medium.com/@busraracoban/how-to-develop-a-spam-classification-model-with-machine-learning-d695f7db9693 📚






