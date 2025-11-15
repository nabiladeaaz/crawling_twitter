# Twitter Crawling — *Free Palestine* Hashtag Dataset

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![snscrape](https://img.shields.io/badge/snscrape-Twitter%20Scraper-green)](https://github.com/JustAnotherArchivist/snscrape)

This project was developed by:
1. Nabila Dea A.
2. Nadhira Arum P.
3. Aqila Huwaida E. J.
4. Fahsa Mayrazzaq N. P.
5. Rosita Dwi F.
6. Ronaldo Situmorang
7. Nur Aini Rahayu P. L.
8. Jesica Permata P.

---

A Python-based project that crawls public posts from Twitter/X using **snscrape**, focusing on content related to **#FreePalestine** and other solidarity hashtags.  
This project provides a raw text dataset suitable for **sentiment analysis, NLP research, topic modeling, and digital activism studies**.

---

## 🚀 Features

- Crawls tweets containing hashtags such as:
  - **#FreePalestine**
  - **#Gaza**
  - **#GazaGenocide**
  - **#VoiceOfGaza**
- Extracts:
  - Tweet text  
  - Embedded hashtags  
  - Tweet URL  
  - Date (if included in the crawl)
- Exports results into a clean `.txt` file.
- Includes a Jupyter Notebook demonstrating the crawling workflow.

---

## 📂 Repository Structure

├── Crawling_Data.ipynb # Main notebook containing the scraping workflow

├── hasil_crawling.txt # Raw tweet dataset from crawling

└── README.md # Project documentation


---

## 📊 Potential Extensions

- Sentiment analysis (VADER, TextBlob, Transformer models)
- Topic modeling (LDA, BERTopic)
- Word frequency & hashtag visualization
- Translation for multilingual NLP
- Streamlit dashboard for real-time exploration

## ⚖️ Ethical Notes

- All collected tweets are publicly accessible.
- Use the dataset for educational and research purposes only.
- Respect privacy and the Twitter/X Terms of Service.
