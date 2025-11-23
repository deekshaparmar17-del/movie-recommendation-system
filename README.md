# Movie Recommendation System
### Intro to Problem Solving & Programming — Mini Project  
### Domain: Entertainment  

## 📌 Overview  
This project is a simple **content-based movie recommendation system** built entirely inside a Jupyter Notebook.  
It uses movie **genres** and **overviews** to find similarity between films and recommend movies that are most related.

The goal of this project is to demonstrate:
- Basic problem-solving approach  
- Use of Python libraries  
- Application of text vectorization  
- Implementing a functional recommendation feature  

## 🧠 Problem Statement  
People often struggle to decide which movie to watch next.  
This project solves that by recommending similar movies based on:
- Genre  
- Description / overview  

Using machine learning concepts like **TF-IDF** and **cosine similarity**, the system suggests related movies.

## 🎯 Features  
✔ Content-based movie recommendations  
✔ Uses TF-IDF vectorization  
✔ Computes movie similarity  
✔ Simple and beginner-friendly  
✔ No external files required — dataset created in-notebook  

## 📂 Project Structure  
## 🛠️ Technologies Used  
- Python  
- Jupyter Notebook  
- Pandas  
- Scikit-learn  
- TF-IDF Vectorizer  
- Cosine Similarity  

## 📘 How It Works  
1. A small dataset of movies is created inside the notebook  
2. Genres + overview are combined into a single text field  
3. TF-IDF converts the text into numerical vectors  
4. Cosine similarity measures how similar two movies are  
5. A function returns the top recommendations for any chosen movie  

## ▶️ Example Usage  
```python
recommend("Avatar")
output gives : ['Avengers', 'Interstellar', 'Inception']


