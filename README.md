# Real Estate Connector
<img class="img-fluid mb-5" src="http://bntnam.github.io/img/portfolio/real-estate-connector-1.png" alt="">
<img class="img-fluid mb-5" src="http://bntnam.github.io/img/portfolio/real-estate-connector-3.png" alt="">
<img class="img-fluid mb-5" src="http://bntnam.github.io/img/portfolio/real-estate-connector-2.png" alt="">

### 1. Introduction

- Clone project from github and go to project folder: **cd real-estate-connector**
- Setup virtual environment. For Python3 version: **python3 -m venv ./venv**
- Access virtual environment (on MacOS): **source ./venv/bin/activate**
- Install dependencies: **pip install -r requirements.txt**
- Install PostgreSQL, create database and config "database name, username, password" in settings.py
- Create database records from models: **python manage.py migrate**
- Run project: **python manage.py runserver**

### 2. Technologies

- **Backend:** Python, Django.
- **Frontend:** Bootstrap, HTML, CSS and some libraries/tools.
- **Database:** PostgreSQL.

### 3. Features

**User Interface:**
- Signing up / Logging in.
- Searching for real estates.
- Contacting realtors by sending a message.

**Admin Portal:**
- Creating / Deleting / Updating real estate information.
- Creating / Deleting / Updating realtors.
- Creating / Deleting / Updating users.
