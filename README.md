# 🍽️ basic Restaurant Recommendation System 

This is my **first-ever project** — a beginner-level **Restaurant Recommendation System** ! 
It recommends restaurants based on factors like **cuisine**, **ratings**, **price**, and **distance** — 
scrapped data of 6 cities from swiggy!

---

## 📌 Problem Statement

With so many restaurants to choose from, users often struggle to find the best options quickly.  
This project aims to solve that by building a smart system that recommends restaurants based on user preferences.


## ⚙️ Tech Stack

| Area            | Technology               | Description                                      |
|------------------|--------------------------|--------------------------------------------------|
| Backend          | **Flask (Python)**        | Web framework to serve the recommendation logic  |
| Data Handling    | Pandas, NumPy             | For data processing and filtering                |
| Recommendation   | TF-IDF, Cosine Similarity | Content-based filtering on restaurant features   |
     |

---

## 🧠 How It Works

1. User enters restaurant name or selects filters (cuisine, price, rating).
2. App matches user input with restaurant features using **TF-IDF + Cosine Similarity**.
3. Returns top 5 most similar restaurants.
4. Displays them on a simple web page.


(restaurant_recommendation.jpg)



