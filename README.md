# Unified NLP-based News Scoring Framework

## 📌 Overview
This project develops a **multi-dimensional NLP framework** to evaluate news articles. Instead of focusing only on sentiment, the system assigns **four distinct scores**:
- Sentiment  
- Emotion  
- Bias  
- Credibility  

These dimensions help readers better understand the **nature and reliability** of news.

## 🛠 Tools & Libraries
- Python  
- Hugging Face Transformers  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  

## 📊 Dataset
- **MIND dataset** (Microsoft News Dataset).  
- Contains news titles and abstracts.  
- Used for text cleaning, processing, and applying pre-trained models.  

## ⚙️ Implementation
- Preprocessed news text (cleaning, tokenization, stopword removal).  
- Applied multiple **pre-trained transformer models**:  
  - RoBERTa → Sentiment  
  - J-Hartmann Emotion Model → Emotions  
  - NewsBias-BERT → Bias  
  - BERT Fake News → Credibility  
- Normalized and aggregated results into a **unified scoring framework**.  
- Visualized distributions and trends with Matplotlib.  

## 🏆 Results
- Successfully generated **multi-metric scores** for news articles.  
- Validated framework using **manual labeling (100 samples)** and **heuristic rules**.  

## 🚀 Key Takeaways
- Goes beyond traditional sentiment analysis.  
- Provides a **holistic evaluation** of news quality.  
- Can be extended into news recommendation or fact-checking systems.  
