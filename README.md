# 🎬 Movie Review Sentiment Analysis using NLP

## 📌 Project Overview
This project uses Natural Language Processing (NLP) and Machine Learning techniques to analyze movie reviews and classify them as Positive or Negative.

The main goal is to understand the sentiment expressed in movie reviews and predict whether a review represents a positive or negative opinion.

## 🎯 Project Objectives
- Analyze movie review text data.
- Perform text cleaning and preprocessing.
- Convert text into numerical features.
- Build Machine Learning classification models.
- Evaluate model performance.
- Predict sentiment for new movie reviews.

## 📊 Dataset Information
- Dataset Name: IMDB Movie Reviews Dataset
- Total Records: 50,000
- Positive Reviews: 25,000
- Negative Reviews: 25,000
- Input Feature: Review
- Target Variable: Sentiment

## ⚙️ Project Workflow
1. Load the Dataset
2. Data Exploration
3. Check Missing Values
4. Encode Sentiment Labels
5. Train-Test Split
6. Text Cleaning
7. Bag of Words Feature Extraction
8. Model Training
9. Model Prediction
10. Model Evaluation
11. Sentiment Analysis using Gradio

## 🤖 Machine Learning Algorithms
1. Multinomial Naive Bayes
2. Logistic Regression

## 📈 Model Performance

| Evaluation Metric | Naive Bayes | Logistic Regression |
|---|---:|---:|
| Accuracy | 84.91% | 89.02% |
| Precision | 86.99% | 88.93% |
| Recall | 82.10% | 89.14% |
| F1 Score | 84.47% | 89.03% |

**Best Performing Model:** Logistic Regression with 89.02% accuracy.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- CountVectorizer
- Matplotlib
- Seaborn
- Gradio
- Jupyter Notebook

## 💻 How to Run the Project
1. Clone or download this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Download the IMDB dataset.
4. Place `IMDB Dataset.csv` in the project folder.
5. Open the Jupyter Notebook.
6. Run all cells step by step.
7. Enter a movie review to predict its sentiment.

## 🎯 Project Output
The model classifies movie reviews into two categories:

- 😊 Positive Review
- 😞 Negative Review

A Gradio interface is also created to enter movie reviews and display sentiment predictions.

## 👩‍💻 Author
**Gangothri Bandaru**

Aspiring Data Scientist | AI & Machine Learning Enthusiast

## ⭐ Conclusion
This project demonstrates how NLP and Machine Learning can be used to understand human opinions from text data. Logistic Regression achieved the best accuracy of 89.02% in the model comparison.
