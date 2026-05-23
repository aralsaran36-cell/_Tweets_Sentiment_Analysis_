# 🐦 Tweets Sentiment Analysis

A Natural Language Processing (NLP) project that classifies **27,000+ tweets** into 3 sentiment categories (Positive, Negative, Neutral) using **TF-IDF vectorization** and **Random Forest classifier**. Achieved **81% accuracy** after hyperparameter tuning.

---

## 🎯 Problem Statement

Social media generates millions of opinions daily. This project builds an NLP pipeline to automatically classify tweet sentiments — useful for brand monitoring, market research, and public opinion analysis.

---

## 📊 Dataset

- **Size:** 27,000+ tweets
- **Classes:** Positive, Negative, Neutral (3-class classification)
- **Challenge:** Noisy text data with emojis, hashtags, and special characters

---

## 🧠 How It Works

```
Raw tweets (27k+)
        ↓
Text Cleaning (remove noise, emojis, special characters)
        ↓
Preprocessing (lowercase, stopword removal, stemming)
        ↓
TF-IDF Vectorization (text → numerical features)
        ↓
Random Forest Classifier
        ↓
Hyperparameter Tuning
        ↓
81% accuracy on 3-class sentiment classification
```

---

## ✨ Key Results

| Metric | Score |
|---|---|
| Accuracy | 81% |
| Classes | Positive / Negative / Neutral |
| Vectorization | TF-IDF |
| Best Model | Random Forest (after tuning) |

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Python |
| NLP | TF-IDF Vectorization, Text Preprocessing |
| Model | Random Forest Classifier |
| Libraries | Scikit-learn, Pandas, NumPy, NLTK, Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 📦 Installation

```bash
# 1. Clone the repo
git clone https://github.com/aralsaran36-cell/Tweets-Sentiment-Analysis.git
cd Tweets-Sentiment-Analysis

# 2. Install dependencies
pip install pandas numpy scikit-learn nltk matplotlib seaborn

# 3. Open notebook
jupyter notebook Tweets_Sentiment_Analysis.ipynb
```

---

## 📁 Project Structure

```
Tweets-Sentiment-Analysis/
│
├── Tweets_Sentiment_Analysis.ipynb   # Main notebook
├── dataset.csv                        # Tweets dataset
└── README.md
```

---

## 💡 Key Learnings

- Text preprocessing and cleaning for real-world noisy data
- TF-IDF vectorization for converting text to features
- Multi-class classification using Random Forest
- Hyperparameter tuning for better model performance

---

## 👨‍💻 Author

**Saravanan S** — Aspiring AI Engineer
- 📧 aralsaran36@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/feed/)
- 🐙 [GitHub](https://github.com/aralsaran36-cell)
