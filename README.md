# 📝 To Do List (Django)

A simple CRUD-based Task Manager built with Django.  
Users can add, edit, delete, and categorize tasks with deadlines.

---

## 🚀 Features

- Add new tasks
- Edit existing tasks
- Delete tasks (POST-based, secure)
- Categorize tasks (Personal, Work, Study, etc.)
- Set task deadlines
- Clean and beginner-friendly Django structure

---

## 🛠️ Tech Stack

- Python
- Django
- SQLite (default Django DB)
- HTML / CSS (templates)

---

## 📂 Project Structure

```
├── .venv/
├── main/
│   ├── __pycache__/
│   ├── migrations/
│   │   └── __init__.py
│   ├── static/
│   │   └── style.css
│   ├── templates/
│   │   ├── base.html
│   │   ├── delete.html
│   │   ├── edit.html
│   │   └── index.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── todolist/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
├── manage.py
└── requirements.txt
```

---

## ⚙️ Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/your-username/django-task-manager.git
```
2. Navigate to project directory
```
cd django-task-manager
```
3. Install dependencies
```
pip install django
```
4.Run migrations
```
python manage.py migrate
```
5.Start development server
```
python manage.py runserver
```
6.Open in browser
```
http://127.0.0.1:8000/
```


📌 Future Improvements

1.Task completion status
2.User authentication
3.Search & filter tasks
4.Pagination
5.Class-based views
