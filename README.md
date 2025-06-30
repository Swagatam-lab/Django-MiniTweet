"# My Django Project" 


A minimal Twitter-like web application built using Django. Users can sign up, post short tweets, and view tweets from other users. This project is perfect for learning core Django concepts like authentication, models, views, and templates.

## 🚀 Features

- User Registration and Login
- Post short tweets (like Twitter)
- View all tweets from all users
- Delete your own tweets
- Responsive UI with Bootstrap

## 🛠️ Tech Stack

- Python
- Django
- SQLite (default DB)
- HTML, CSS, Bootstrap

## 📂 Project Structure

DjangoMiniTweet/
│
├── mini_tweet/ # Main Django app
├── templates/ # HTML templates
├── static/ # CSS and JS
├── db.sqlite3 # Database file
├── manage.py
└── requirements.txt

bash
Copy
Edit

## 📦 Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/Swagatam-lab/Django-MiniTweet.git
cd Django-MiniTweet
Create a Virtual Environment

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate  # Windows
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run Migrations

bash
Copy
Edit
python manage.py migrate
Start the Server

bash
Copy
Edit
python manage.py runserver
Access the App
Go to: http://127.0.0.1:8000/

🧪 Sample Credentials
Username: testuser

Password: testpass123

📌 Future Improvements
Tweet like/comment functionality

User profiles with profile pics

Follow/unfollow feature

REST API with Django Rest Framework

📃 License
This project is open-source and available under the MIT License.






