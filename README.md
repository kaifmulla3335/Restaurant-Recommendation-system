# 🍽️ Smart Restaurant Recommendation System

A web-based restaurant recommendation system that suggests restaurants based on user preferences such as cuisine, budget, and ratings using **Content-Based Filtering**.

---

## 🚀 Features

- 🔍 Search restaurants by name
- 🍜 Filter by cuisine
- 💰 Budget-based filtering
- ⭐ Rating-based filtering
- 🤖 ML-based recommendations (TF-IDF + Cosine Similarity)
- 🎨 Modern UI (Dashboard Style)
- ⚠️ Error handling (No results / Not found)

---

## 🧠 How It Works

1. User enters:
   - Restaurant Name
   - Cuisine
   - Budget
   - Rating

2. System:
   - Finds the selected restaurant
   - Converts cuisine text into vectors (TF-IDF)
   - Calculates similarity using Cosine Similarity

3. Filters results:
   - Cuisine match
   - Budget
   - Rating

4. Displays top recommended restaurants

---

## 🛠️ Tech Stack

### 💻 Frontend

- HTML
- CSS
- Font Awesome

### ⚙️ Backend

- Python
- Flask

### 📊 Data Processing

- Pandas
- NumPy

### 🤖 Machine Learning

- Scikit-learn
  - TF-IDF Vectorizer
  - Cosine Similarity

---

## 📂 Project Structure

Restaurant-Recommendation-System/
│
├── Flask/
│ ├── app1.py
│ ├── restaurant1.csv
│ ├── templates/
│ │ ├── index.html
│ │ ├── recommend.html
│ │ ├── result.html
│ │ ├── error.html
│ │
│ ├── static/
│
├── screenshots/
│ ├── home.png
│ ├── form.png
│ ├── result.png
│
│
└── README.md

---

## 📸 Screenshots

### 🏠 Home Page

![Home Page](screenshots/index.png)

### 🔍 Recommendation Page

![Form Page](screenshots/form.png)

### 📊 Result Page

![Result Page](screenshots/result.png)
![Result Page](screenshots/result2.png)

---

## 📊 Dataset

The dataset contains:

- Restaurant Name
- Rating
- Mean Rating
- Cuisines
- Cost

### Example:

Qaswa,4.3,4.1,north indian,800

---

## 📌 Conclusion

This project demonstrates how machine learning can be used to build a real-world recommendation system with a modern UI and filtering logic.

---

## 👨‍💻 Developed By

**Mohammadkaif Mulla**
