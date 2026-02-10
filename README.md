# book-recommendation-system
Flask-based Book Recommendation System using content-based and collaborative filtering. Features user authentication, search history tracking, and personalized recommendations. Built with Python, Flask, SQLAlchemy, SQLite, Bootstrap, Pandas, and NumPy.
# 📚 Book Recommendation System

A web-based **Book Recommendation System** built using **Python, Flask, HTML, CSS**, and **Machine Learning**. The system recommends books based on user input using similarity-based filtering and provides a clean, user-friendly interface with authentication.

# 🚀 Features

* 🔐 User Authentication (Sign Up / Login / Logout)
* 📖 Personalized book recommendations
* 🔍 Search functionality for books
* 🧠 Machine Learning model using similarity scores
* 📊 Displays book title, author, and cover image
* 🗂️ User dashboard with search history
* 📱 Responsive UI for different screen sizes

## 🛠️ Tech Stack

* **Backend:** Python, Flask
* **Frontend:** HTML, CSS, Bootstrap
* **Machine Learning:** NumPy, Pandas, Pickle
* **Model Type:** Content-based filtering
* **Database:** SQLite (for user authentication & history)

# 🧠 Machine Learning Overview

* Uses a preprocessed dataset of books
* Computes similarity scores between books
* Recommends top similar books based on user selection
* ML model serialized using `.pkl` files

# 🔐 Validation & Security

* Email validation (must contain `@`)
* Password confirmation check
* Prevents duplicate user registration
* Session-based authentication

## 📂 Project Structure

```
├── app.py
├── auth.py
├── recommend.py
├── templates/
│   ├── login.html
│   ├── signup.html
│   ├── index.html
│   └── dashboard.html
├── static/
│   ├── css/
│   └── images/
├── model/
│   ├── similarity.pkl
│   ├── books.pkl
│   └── pt.pkl
├── notebooks/
│   └── model_training.ipynb
└── README.md
```

# ⚙️ Installation & Setup

1. Clone the repository

   ```bash
   git clone https://github.com/KBcode003/book-recommendation-system.git
   ```
2. Navigate to the project directory

   ```bash
   cd book-recommendation-system
   ```
3. Install required dependencies

   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask app

   ```bash
   python app.py
   ```
5. Open browser and go to:

   ```
   http://127.0.0.1:5000/
   ```
# 👥 Collaboration

This project was developed collaboratively using GitHub. Contributors worked on backend logic, ML integration, and frontend design using proper version control practices.

# 🎯 Use Case

* Academic project
* Internship portfolio project
* Beginner-friendly ML + Web Development integration

# 📌 Future Enhancements

* User-based collaborative filtering
* Ratings & reviews system
* Deployment on cloud (Render / AWS)
* Improved UI with React

# 👩‍💻 Author

**Krishala Bhattarai**
Final Year CSE Student | Aspiring Web & ML Developer-


