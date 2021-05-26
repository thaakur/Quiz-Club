# Quiz Club

This is an online quiz organizing website project, developed using Python's web framework Django.<br>

## Getting started with development
Dependencies:
- Python 3.6.x
- Django 1.11.x

### 1. Go to lets_quiz folder
```bash
cd lets_quiz
```

### 2. Create the virtualenv and install requirements
```bash
py -m venv lets_quiz
pip install -r requirements.txt
```

### 3. Setup the database and Run database migrations
```bash
py manage.py migrate
```

### 4. Create superuser for admin access
```bash
py manage.py createsuperuser
```

### 5. Run the server
```bash
py manage.py runserver
```
