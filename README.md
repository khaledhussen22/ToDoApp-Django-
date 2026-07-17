# 📝 Django ToDo App

A simple ToDo List application built with Django that supports basic CRUD operations.

## Features

- ➕ Add tasks
- ✏️ Update tasks
- ❌ Delete tasks
- 📋 View all tasks
- 🔐 Django Admin

## Tech Stack

- Python
- Django
- SQLite
- HTML
- CSS

## Run Locally

```bash
git clone https://github.com/khaledhussen22/ToDoApp-Django-.git
cd ToDoApp-Django-
python -m venv venv
venv\Scripts\activate
pip install django
python manage.py migrate
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000/
```

## Admin

```bash
python manage.py createsuperuser
```

Then open:

```
http://127.0.0.1:8000/admin/
```

---
Built as a beginner Django CRUD project.
