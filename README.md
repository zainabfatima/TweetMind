# 🧠 Abstractive Summarization and Named Entity Recognition on Twitter Dataset

This project performs two advanced NLP tasks on a Twitter dataset:
1. 🏷️ **Named Entity Recognition (NER)** using a BERTweet NER model
2. ✍️ **Abstractive Summarization** using Google's Pegasus model

It also includes full data cleaning, entity extraction, date filtering, and Hugging Face pipeline usage.

---

## 🔥 Features

- 🧹 Cleans raw tweet data (URLs, emojis, line breaks, usernames)
- 📆 Filters tweets by date
- 🏷 Named Entity Recognition using pretrained **BERTweet (TweebankNLP)**
- ✍️ Abstractive summarization using **Pegasus XSUM**
- 📤 Saves outputs to CSV
- ✅ Compatible with Hugging Face Transformers

---

## 📁 File Structure

Abstractive-summarization-and-NER-of-Twitter-dataset/
├── notebook.ipynb # Main Jupyter notebook containing full workflow
├── dataset.csv # (Expected) Tweet dataset with tweet_text and tweet_date
└── latest_download.csv # Output: Tweets with NER predictions

yaml
Copy
Edit

---

## 🛠 How to Run

### 1. Install dependencies

```bash
pip install transformers==4.6.0 torch==1.8.2 sentencepiece emoji
