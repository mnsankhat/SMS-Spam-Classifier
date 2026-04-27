# 📩 SMS Spam Detection System

A Machine Learning + NLP based web application that classifies SMS/Email messages as **Spam** or **Not Spam**.

---

## 🚀 Features

- Classifies messages in real-time
- Text preprocessing using NLP techniques
- Clean and interactive UI using Streamlit
- Fast and accurate predictions

---

## 🧠 Machine Learning & NLP Concepts Used

- Text Preprocessing
  - Lowercasing
  - Tokenization (NLTK)
  - Stopword Removal
  - Stemming (Porter Stemmer)
- Feature Extraction
  - CountVectorizer / TF-IDF
- Model Training
  - Classification Algorithm (Naive Bayes / Logistic Regression)

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** NLTK, Scikit-learn, Pandas, NumPy
- **Frontend:** Streamlit
- **Tools:** Jupyter Notebook, Git, GitHub

---

## 📂 Project Structure


---

## ⚙️ How It Works

1. User enters a message
2. Text is preprocessed:
   - Remove punctuation & stopwords
   - Apply stemming
3. Convert text into numerical form using vectorizer
4. Model predicts:
   - Spam ✅
   - Not Spam ❌

---

## ▶️ Run Locally

### 1. Clone Repository
```bash
git clone https://github.com/maheshsankhat/SMS-Spam-Classifier
cd spam-detection
