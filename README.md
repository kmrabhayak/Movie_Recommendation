# 🎥 Movie Recommendation System

A content-based movie recommendation system built with Python and Django, offering personalized suggestions using cosine similarity algorithms. Powered by a clean UI and backed by a trained ML pipeline.

---

## 📘 Overview

This system analyzes movie metadata and calculates cosine similarity scores to recommend films that share similar features. Users can enter a movie title and instantly get suggestions that match in genre, keywords, and cast.

---

## 💡 Key Features

- 🎯 Content-based filtering with **cosine similarity**
- 📚 Uses vectorized features from movies like genre, cast, and overview
- 📈 Preprocessed dataset with TF-IDF vectorizer
- 🌐 Frontend served via Django templates
- 🔍 Search-based movie lookup interface

---

## 🛠 Tech Stack

| Layer       | Technologies                      |
|------------|-----------------------------------|
| Backend     | Django, SQLite                    |
| ML & Analysis | Scikit-learn, Pandas, NumPy        |
| Frontend    | HTML, CSS, JavaScript             |
| Notebook    | Jupyter for analysis & modeling   |

---

## 📁 Project Structure
Movie_Recommendation/ 
├── recommender/ # Django app logic 
├── static/ # CSS and JS files 
├── templates/ # HTML templates 
├── movie_recommendation/ # Django project settings 
├── readme_images/ # Visuals for documentation 
├── Movie_Recommendation_System_Complete_Guide.ipynb # Model notebook 
├── db.sqlite3 # SQLite DB ├── manage.py # Django manager
├── requirements.txt # Dependencies


---

## 🚀 Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/kmrabhayak/Movie_Recommendation.git
cd Movie_Recommendation
```
### 2. Set Up Python Environment
```bash
python3 -m venv env
source env/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
### 4. Run the Server
```bash
python manage.py runserver
```

Navigate to http://127.0.0.1:8000/ in your browser.


---

### 👨‍💻 Author
Created by Abhay Kumar

### 📜 License
This project is open-sourced under the MIT License. See the LICENSE file for details.



