# Sentiment Analysis of Amazon Electronics Reviews

## Overview
This project performs sentiment analysis on **50,000+ Amazon electronics product reviews** using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.  
The goal is to classify reviews into **Positive, Negative, and Neutral categories** while ensuring **model interpretability** through visualizations.

---

## Tech Stack
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Scikit‑Learn, NLTK, TextBlob, VADER, Seaborn, Matplotlib, WordCloud  
- **Approach**: NLP preprocessing → Sentiment scoring → TF‑IDF vectorization → Logistic Regression classification → Evaluation & visualization  

---

## Steps Implemented

### 1. Data Preprocessing
- Cleaned raw text using **BeautifulSoup** (HTML removal) and **regular expression** (punctuation, special characters).  
- Removed **stopwords** with NLTK.  
- Normalized text for consistent analysis.  

### 2. Sentiment Analysis
- **TextBlob** → Generated polarity scores.  
- **VADER** → Lexicon‑based sentiment categories (Positive, Negative, Neutral).  

### 3. Feature Extraction
- Applied **TF‑IDF vectorization** with 5,000 features.  

### 4. Model Training
- Trained a **Logistic Regression classifier**.  
- Achieved **87% accuracy** in predicting sentiment categories.  

### 5. Model Evaluation
- **Confusion Matrix Heatmap** → Visualized classification performance.  
- **Classification Report** → Precision, Recall, F1‑score.  

### 6. Interpretability & Visualization
- **Coefficient plots** → Top positive & negative words influencing predictions.  
- **WordClouds** → Frequent words and most influential sentiment drivers.  
- **Seaborn count plots** → Sentiment distribution across dataset.  

---

## Results
- **Accuracy**: 87%  
- **Top Positive Indicators**: *excellent, perfect, value, amazing*  
- **Top Negative Indicators**: *poor, bad, delay, worst*  
- Clear interpretability through **WordClouds** and **bar plots** of influential words.  

---

## Visualizations
- Confusion Matrix Heatmap  
- WordClouds for Positive & Negative words  
- Sentiment Distribution Plot  
