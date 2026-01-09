# Flipkart_Review_Analysis

# Flipkart Reviews Sentiment Analysis

## 📌 Project Overview
This project performs **sentiment analysis on Flipkart product reviews** to understand customer opinions and classify reviews as **Positive, Negative, or Neutral**.

The goal is to simulate a **real-world e-commerce analytics use case** where customer feedback is transformed into actionable insights for product and business teams.

---

## 🎯 Business Problem
E-commerce platforms receive thousands of customer reviews daily.  
Manually analyzing them is impossible.

This project answers:
- What percentage of customers are satisfied?
- What are the most common complaint themes?
- Can sentiment be automatically classified with reasonable accuracy?

---

## 🧠 Approach & Methodology

### 1. Data Understanding
- Dataset contains customer reviews and ratings
- Identified missing values, duplicates, and noisy text

### 2. Data Cleaning & Preprocessing
- Removed punctuation, numbers, and special characters
- Converted text to lowercase
- Tokenization and stopword removal
- Lemmatization for better text normalization

### 3. Sentiment Labeling
- Sentiment scores generated using NLP techniques
- Reviews classified into:
  - Positive
  - Neutral
  - Negative

### 4. Exploratory Data Analysis (EDA)
- Distribution of sentiments
- Word frequency analysis
- WordCloud for positive and negative reviews
- Review length vs sentiment insights

### 5. Model Building
- Text vectorization using **TF-IDF**
- Machine Learning model:
  - Logistic Regression (baseline)
- Model evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report

---

## 📊 Key Insights
- Majority of reviews are **positively skewed**
- Negative reviews frequently mention:
  - Delivery issues
  - Product quality mismatch
- Short reviews tend to be extreme (very positive or very negative)

---

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy**
- **NLTK / TextBlob**
- **Scikit-learn**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flipkart-reviews-sentiment-analysis.git
