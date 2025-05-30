# Fake News Detection using TF-IDF and Logistic Regression

This project applies Natural Language Processing and Machine Learning to classify news articles as **Real** or **Fake**. The model uses **TF-IDF vectorization** for feature extraction and **Logistic Regression** for classification. It is deployed as a web app using **Streamlit** for real-time user interaction.

## 🔍 Features
- Input a news article through a clean Streamlit interface
- Preprocesses text using NLP techniques (lowercasing, stopword removal, lemmatization)
- Applies TF-IDF for text vectorization
- Predicts using a trained Logistic Regression model
- Classifies articles as Real or Fake

## 📁 Files
- `Fake.csv` & `True.csv`: Labeled datasets
- `vectorizer.jb`: Saved TF-IDF vectorizer
- `lr_model.jb`: Trained Logistic Regression model
- `app.ipynb`: Streamlit web app code

## 🚀 How to Run
```bash
pip install -r requirements.txt
streamlit run app.ipynb
