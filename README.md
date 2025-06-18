# 🧩 Django Basic Boilerplate

A clean and minimal Django boilerplate to kickstart new projects with a structured setup for settings, apps, templates, and static files.

---

## 🚀 Features

- Modular settings
- Structured project layout
- Pre-configured templates and static directories
- Environment variable support via `.env`
- App structure ready for scaling

---

## 📁 Project Structure
```
Project
├── LICENSE
├── project
│   ├── app
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── __init__.py
│   │   ├── migrations
│   │   │   ├── __init__.py
│   │   │   └── __pycache__
│   │   │       └── __init__.cpython-312.pyc
│   │   ├── models.py
│   │   ├── __pycache__
│   │   │   ├── admin.cpython-312.pyc
│   │   │   ├── apps.cpython-312.pyc
│   │   │   ├── __init__.cpython-312.pyc
│   │   │   ├── models.cpython-312.pyc
│   │   │   ├── urls.cpython-312.pyc
│   │   │   └── views.cpython-312.pyc
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── db.sqlite3
│   ├── Django-Boilerplate
│   │   └── project
│   │       └── static
│   │           ├── admin
│   │           │   ├── css
│   │           │   ├── img
│   │           │   └── js
│   │           └── style.css
│   ├── manage.py
│   ├── project
│   │   ├── asgi.py
│   │   ├── __init__.py
│   │   ├── __pycache__
│   │   │   ├── __init__.cpython-312.pyc
│   │   │   ├── settings.cpython-312.pyc
│   │   │   ├── urls.cpython-312.pyc
│   │   │   └── wsgi.cpython-312.pyc
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── requirements.txt
│   ├── static
│   │   └── style.css
│   └── templates
│       ├── base.html
│       └── index.html
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/kushalyadav0/Django-Boilerplate.git
cd Django-Boilerplate

```
### 2. Set Up Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Requirements
```bash
pip install -r requirements.txt
```

### 4. Setup `.env`
Create a `.env` file based on the provided example:
```bash
SECRET_KEY=your-django-secret-key
DEBUG=True
```

### 5. Run Migrations
```bash
python manage.py migrate
```

### 6. Start Development Server
```bash
python manage.py runserver
```
Visit: http://127.0.0.1:8000

### 🔐 Environment Variables
Use the `.env` file to store secrets and config. Add your:
```bash
SECRET_KEY

DEBUG

DATABASE_URL (for production, if needed)

API_KEY
```
### 🪪 License
This project is licensed under the MIT License.