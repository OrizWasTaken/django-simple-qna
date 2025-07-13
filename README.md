# Django Q&A Platform

A simple Stack Overflow-style Q&A web application built with Django. Users can register, post questions, answer others, and browse existing discussions.

## 🚀 Features

- User registration and login
- Ask questions
- Answer questions
- Accept best answer
- Vote on answers (basic form-based)
- User profiles (basic)

## 🛠 Built With

- [Django](https://www.djangoproject.com/) (Python)
- SQLite (default dev DB)
- HTML/CSS (Django templates)

## 📦 Installation

1. **Clone the repo**

```bash
git clone https://github.com/your-username/django-qa-platform.git
cd django-qa-platform
````

2. **Set up virtual environment**

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run migrations**

```bash
python manage.py migrate
```

5. **Create a superuser (admin account)**

```bash
python manage.py createsuperuser
```

6. **Run the development server**

```bash
python manage.py runserver
```

Then go to `http://127.0.0.1:8000` in your browser.

## 👤 Users

* Use the **Django admin panel** at `/admin` to manage questions, answers, and users.

## 📝 License

This project is open source and free to use.
