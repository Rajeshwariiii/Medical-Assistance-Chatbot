# Medical-Assistance-Chatbot
A smart Medical Assistant Chatbot that predicts possible diseases based on user-described symptoms using **Natural Language Processing (NLP)** and **Machine Learning (ML)**. 

This project demonstrates how to combine **TF-IDF vectorization**, **text preprocessing**, and **ensemble classification models** in a Flask-powered web interface.
## 🔍 Features

- Takes free-form symptom input from users (e.g., "I have a rash and feel dizzy")
- Uses **NLP** to preprocess text (tokenizing, stemming, vectorizing)
- Uses a **Voting Classifier** with Naive Bayes, Random Forest, SVM, and Logistic Regression
- Predicts the most probable disease based on trained data
- Flask-based web interface for easy interaction
## 📦 Installation & Setup

### 🔧 Environment Setup

First, make sure you have **Python 3.7+** installed.

### 1️⃣ Clone the Repository
git clone https://github.com/your-username/Medical-Assistant-Chatbot.git

cd Medical-Assistant-Chatbot

2️⃣ Create Virtual Environment (Recommended)

python -m venv venv

source venv/bin/activate     # On macOS/Linux

venv\Scripts\activate        # On Windows

3️⃣ Install Dependencies
pip install pandas nltk scikit-learn flask joblib

Make sure to download NLTK resources:

### Running the Project
python app.py

If you want to retrain the model from scratch:
python model_training.py

✅ Advantages
User-Friendly Symptom Input

Accepts natural language symptom descriptions instead of requiring users to select from a predefined list.

Accurate Disease Prediction

Uses an ensemble of machine learning models (Naive Bayes, Random Forest, SVM, and Logistic Regression) to ensure high accuracy (up to 97%).

Real-Time Interaction

Integrated with a Flask web app, allowing users to get instant predictions through a simple and clean interface.

Reusable and Scalable

Pretrained models and vectorizers are saved using Joblib, making it easy to integrate into mobile apps, APIs, or other platforms.
 
