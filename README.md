# 📒 Notes Management System

A simple web-based Notes Management System built using **Flask**, **SQLite**, **SQLAlchemy**, and **Flask-Login**. This app allows users to securely register, log in, create, and manage their personal notes.

## 🚀 Features

- 🔐 User Authentication (Sign Up / Login / Logout)
- 📝 Create, view, and delete notes
- 🔒 Passwords are hashed for security
- 📦 SQLite database integration via SQLAlchemy
- 🌐 Clean and simple front-end using HTML, CSS, and Jinja2 templates

## 🛠️ Tech Stack

- **Backend**: Python, Flask, Flask-Login, SQLAlchemy
- **Frontend**: HTML, CSS, Jinja2
- **Database**: SQLite

## 📂 Project Structure

```

NOTES-MANAGEMENT-SYSTEM/
│
├── website/                 # Main Flask package
│   ├── static/              # Static files (CSS, JS)
│   ├── templates/           # HTML templates
│   ├── **init**.py          # Flask app factory
│   ├── auth.py              # Authentication routes
│   ├── views.py             # Main app routes
│   └── models.py            # Database models
│
├── venv/                    # Virtual environment (not pushed to GitHub)
├── main.py                  # Entry point for the Flask app
└── README.md                # Project documentation

````

## 🧑‍💻 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/aishwaryalakshmy/NOTES-MANAGEMENT-SYSTEM.git
cd NOTES-MANAGEMENT-SYSTEM
````

### 2. Create and Activate Virtual Environment (Optional but recommended)

```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, install manually:

```bash
pip install flask flask_sqlalchemy flask_login werkzeug
```

### 4. Run the App

```bash
python main.py
```

Then open your browser and go to: `http://127.0.0.1:5000`

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/45c55870-c7a6-4013-a023-b5cdbf02d405)

![image](https://github.com/user-attachments/assets/befae47a-e781-4e8d-8f6b-c92174399f0c)

## 🧩 Future Improvements

* Add note editing functionality
* Use PostgreSQL or MySQL for production
* Responsive UI with Bootstrap or TailwindCSS
* Tagging or categorization of notes
* Search/filter functionality

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License.

---

### Made with ❤️ by [Aishwarya Lakshmy](https://github.com/aishwaryalakshmy)

```

---

Let me know if you'd like me to generate a `requirements.txt`, add screenshots, or tailor this for deployment on services like Heroku or Render.
```
