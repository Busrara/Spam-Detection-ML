# Spam-Detection-ML

This project is designed to classify SMS messages as either "ham" (legitimate) or "spam" using machine learning models like Random Forest and Naive Bayes.

🟤 Libraries Used

The following libraries are used in this project:

⚫ pandas for data handling
⚫ numpy for numerical operations
⚫ scikit-learn for machine learning models
⚫ imblearn for oversampling techniques
⚫ matplotlib and seaborn for data visualization
⚫ nltk for natural language processing

🟤 Dataset

This project uses a dataset of SMS messages. It contains two classes:

ham: Legitimate messages
spam: Spam messages
The dataset is pre-processed and cleaned before using machine learning models.

🟢 How It Works

# 1. Data Preprocessing:
⚫ The raw data is loaded and cleaned.
⚫ Text is tokenized and transformed using TF-IDF vectorization.

# 2. SMOTE Oversampling:
⚫ The class imbalance is handled using SMOTE (Synthetic Minority Over-sampling Technique).

# 3.Model Training:
- Two machine learning models are used:
⚫ Random Forest Classifier
⚫ Naive Bayes Classifier

# Model Evaluation:
Accuracy, confusion matrix, and classification report are used to evaluate the model's performance.

🔴 Results

The models are evaluated on different metrics including accuracy, precision, recall, and F1-score.

# Random Forest:
Accuracy: 99.4%
Confusion Matrix:
True Positive (TP): 1443
False Positive (FP): 3
False Negative (FN): 14
True Negative (TN): 1435

# Naive Bayes:
Accuracy: 98.6%
Confusion Matrix:
True Positive (TP): 1435
False Positive (FP): 22
False Negative (FN): 16
True Negative (TN): 1422



