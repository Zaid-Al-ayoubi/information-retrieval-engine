# 🔍 Information Retrieval Engine

A lightweight search engine built with Python that ranks 
documents by relevance using TF-IDF and Cosine Similarity,
with built-in spell correction using Soundex algorithm.

## ✨ Features

- **TF-IDF Ranking** — ranks files by relevance to query
- **Cosine Similarity** — measures similarity between query and documents
- **Inverted Index** — fast word lookup across all files
- **Soundex Spell Correction** — handles typos and misspellings
- **Phrase Search** — search exact phrases using quotes

## 📊 Results

| Metric | Score |
|--------|-------|
| Search Accuracy | 100% |
| Files Tested | 4 |

## 🛠️ Tech Stack

Python · Scikit-learn · TF-IDF · Cosine Similarity · Soundex

## 🚀 How to Run

# Install dependencies
pip install -r requirements.txt

# Run
python information_retrieval_engine.py

## 📁 How It Works

1. Reads all .txt files from a directory
2. Builds an Inverted Index for fast lookup
3. User enters a query
4. Soundex corrects spelling mistakes
5. TF-IDF + Cosine ranks results by relevance
6. Returns ranked list of most relevant files
