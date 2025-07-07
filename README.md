# 🎬 Movie Review Sentiment Analysis

This project performs sentiment analysis on movie reviews to classify them as **positive** or **negative** using Natural Language Processing (NLP) techniques.

## 📂 Dataset
- The dataset used is `Restaurant_Reviews.tsv` (can be replaced with a movie review dataset).
- Each entry contains a user review and its associated sentiment label (positive or negative).

## 🧠 Model Workflow

1. **Data Preprocessing**
   - Lowercasing
   - Removing punctuation and non-alphabetic characters
   - Removing stopwords
   - Stemming using PorterStemmer

2. **Feature Extraction**
   - Bag-of-Words (CountVectorizer)

3. **Model Training**
   - Naive Bayes or Logistic Regression or SVM can be applied
   - Accuracy and confusion matrix used for evaluation

## 🛠️ Technologies Used
- Python
- NLTK
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (for optional visualizations)

## 📈 Example Output
- After training the model, it can predict if a new review is:
  - ✅ Positive
  - ❌ Negative

## 🚀 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/Movies-Reviews-Sentiment-Analysis
   cd Movies-Reviews-Sentiment-Analysis
2. Install dependencies
   ```bash
     pip install -r requirements.txt
3. Run the python Script
  ```bash
    python natural_language_processing.py

