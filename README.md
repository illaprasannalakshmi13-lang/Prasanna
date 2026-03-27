# Prasanna
🛡 AI-Based Phishing Email Detection System 📌 Project Overview

This project focuses on detecting phishing emails using Artificial Intelligence techniques. The system analyzes email content using Natural Language Processing (NLP) and classifies it as either phishing or safe using a Machine Learning model.

Phishing attacks are one of the most common cyber threats today, and this system aims to automate detection to reduce digital fraud.

🎯 Problem Statement

Phishing emails attempt to trick users into revealing sensitive information such as passwords, banking details, and OTPs. Manual detection is unreliable, so we developed an automated AI-based detection system.

💡 Proposed Solution

We developed a web-based application that:

Takes email content as input

Processes the text using TF-IDF vectorization

Uses Logistic Regression to classify the email

Displays prediction with confidence score

🛠 Technologies Used

Python

Scikit-learn

TF-IDF (Text Feature Extraction)

Logistic Regression

Streamlit (Web Application Framework)

Kaggle Phishing Email Dataset

🧠 How It Works

User enters email content in the web application.

The text is converted into numerical features using TF-IDF.

The trained machine learning model analyzes the features.

The system predicts whether the email is phishing or safe.

The result is displayed with confidence percentage.

📊 Model Performance

The model was trained using a real-world phishing dataset. It achieved high classification accuracy on test data.

(Insert your actual accuracy value)

🚀 How to Run the Project

Install Dependencies pip install -r requirements.txt
Train the Model python model.py
Run the Web Application streamlit run app.py 🔮 Future Enhancements
Integration with Gmail

Deep learning-based classification

URL and attachment analysis

Cloud deployment

📌 Conclusion

This project demonstrates how Machine Learning and NLP can be applied to solve real-world cyber security problems by automatically detecting phishing emails.
