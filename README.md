# 📺 Netflix Data Analysis

## 📖 Overview
This project applies Natural Language Processing (NLP) to analyze customer reviews and classify them as positive, negative, or neutral.
It demonstrates skills in text preprocessing, feature extraction, and machine learning model training.

---

## 🗂 Dataset
- Source: [IMDb Movie Reviews Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)  
- Records: ~50,000  
- Features: review text, sentiment label  

---

## ⚙️ Methodology
1. **Data Preprocessing**
   - Tokenization, stopword removal, stemming
   - Converted text to numeric features using TF-IDF
2. **Model Training**
   - Logistic Regression, Naive Bayes
3. **Evaluation**
   - Accuracy, Precision, Recall, F1-score

---

## 📊 Key Insights
- Text preprocessing significantly improves model performance.  
- Logistic Regression and Naive Bayes work best for sentiment classification.  
  
---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 🚀 How to Run
1. Clone the repo
2. Create a virtual environment: 
   ```bash
   conda create -n sentiment
   conda activate sentiment
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

   ```
4. Run the notebook cell by cell to preprocess data, train models, and view results.
