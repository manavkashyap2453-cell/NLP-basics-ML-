# NLP Pipeline 🚀

This repository contains a complete **Natural Language Processing (NLP) pipeline** built in Python, showcasing text preprocessing, feature extraction, and model training for emotion classification.

## 📂 Project Overview
The notebook demonstrates how to transform raw text into structured features and train machine learning models to classify emotions. It covers the entire workflow from **data ingestion** to **model persistence**.

## 🔑 Key Steps
- **Data Loading**: Import text dataset with emotion labels.  
- **Preprocessing**:
  - Lowercasing text  
  - Removing punctuation, numbers, and emojis  
  - Tokenization and stopword removal (NLTK)  
- **Label Encoding**: Convert categorical emotion labels into numeric form.  
- **Train/Test Split**: Split dataset into training and testing sets.  
- **Vectorization**:
  - Bag of Words (CountVectorizer)  
  - TF-IDF (TfidfVectorizer)  
- **Model Training**:
  - Logistic Regression  
  - Naive Bayes  
- **Evaluation**: Classification reports with precision, recall, and F1-score.  
- **Model Persistence**: Save trained model using `pickle` for reuse.

## 📊 Results
- **Logistic Regression** achieved ~89% accuracy with balanced precision/recall across classes.  
- **Naive Bayes** performed moderately (~77% accuracy), with strong results for some classes but weaker for others.  

## 🛠️ Tech Stack
- **Python** (NumPy, Pandas, Matplotlib, Seaborn)  
- **NLTK** for text preprocessing  
- **Scikit-learn** for encoding, vectorization, model training, and evaluation  

## 📌 Next Steps
- Improve preprocessing (lemmatization, stemming).  
- Experiment with advanced models (SVM, Random Forest, Deep Learning).  
- Deploy the trained model as an API or web app.  
