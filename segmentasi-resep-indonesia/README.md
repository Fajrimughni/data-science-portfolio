# 🍲 What Do You Like: Indonesian Food Recommendation

This project explores clustering of Indonesian recipes based on nutritional information and title similarity. Using unsupervised learning methods, it aims to segment recipes into meaningful groups and recommend relevant dishes based on user preferences.

[⬅️ Back to Portfolio Home](../README.md)

---

## 📌 Project Overview

- **Objective**: Cluster Indonesian recipes and build a recommendation system using TF-IDF and KMeans.
- **Dataset**: Recipes and nutritional values (sourced manually and processed).
- **Tools**: Python, Pandas, Scikit-learn, Streamlit.
- **Techniques**: Text Vectorization (TF-IDF), KMeans Clustering, Streamlit App Deployment.

---

## 📁 Folder Structure
segmentasi-resep-indonesia/
├── README.md
├── data/
│ ├── raw/ <- Original raw data
│ └── processed/ <- Cleaned & structured data
├── notebooks/
│ ├── eda_clustering.ipynb <- Exploratory analysis and clustering
│ └── tfidf_preprocessing.ipynb <- Text processing and feature extraction
├── app/
│ └── streamlit_app.py <- Streamlit web app code
├── images/
│ ├── cluster_plot.png
│ └── app_screenshot.png
├── requirements.txt
└── LICENSE


---

## 📊 Results

- Clustered recipes based on both nutritional profiles and title similarity.
- Successfully deployed an interactive recommendation dashboard using Streamlit.

📷 *Example Visualizations*:

![Cluster Plot]("C:\Users\ASUS\data-science-portfolio\segmentasi-resep-indonesia\images\pola geografis pemilihan makanan.png")

---

## ▶️ Live App

You can try the interactive version here :

👉 [Streamlit App](https://streamlit.app/link)

---

## 🔧 How to Run

```bash
pip install -r requirements.txt
streamlit run app/streamlit_app.py

