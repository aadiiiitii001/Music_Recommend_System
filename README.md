# 🎵 Music Recommendation System

A **content-based music recommendation system** that suggests similar songs based on **song lyrics** using **TF-IDF vectorization** and **cosine similarity**.  
The application is built using **Python** and **Streamlit** to provide fast, interactive, and user-friendly music recommendations.

---

## 📌 Project Overview

This Music Recommendation System analyzes song lyrics to recommend tracks with similar themes, vocabulary, and context.  
Unlike collaborative filtering, this system does **not require user history**, making it effective for solving the **cold-start problem**.

When a user selects a song, the system returns the **top N most similar songs** based on lyrical similarity.

---

## 🚀 Features

- Content-based music recommendation
- Lyrics-based similarity using **TF-IDF**
- Cosine similarity for song matching
- Interactive UI built with **Streamlit**
- Fast and lightweight recommendation engine
- Explainable and transparent recommendations

---

## 🧠 How It Works

1. Load and preprocess song lyrics data  
2. Convert lyrics into numerical vectors using **TF-IDF**  
3. Compute **cosine similarity** between all song vectors  
4. Recommend the **top N similar songs** for a selected track  

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **NLP Techniques:** TF-IDF, Cosine Similarity  
- **Frontend:** Streamlit  

---

## 📂 Project Structure
music-recommendation-system/
'''
│
├── data/
│ └── songs.csv
│
├── app.py
├── model.py
├── requirements.txt
└── README.md
'''
Install dependencies
pip install -r requirements.txt

3️⃣ Run the application
streamlit run app.py
