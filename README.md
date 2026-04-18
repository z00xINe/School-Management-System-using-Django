# School Management System (Django)

A web-based School Management System built using Django framework to manage students, teachers, classes, and academic operations efficiently.

## Overview
This project is designed as a practical implementation of a school system where different entities (students, teachers, classes) interact together. It demonstrates backend development using Django and follows MVC (Model-View-Template) architecture.

## Features
- Manage Students and Teachers
- Class Management
- Enrollment System
- Admin Panel Integration
- Organized Models and Relationships
- Basic Authentication & Access Control
- Clean and structured Django apps

## Technologies Used
- Backend: Django (Python)
- Database: SQLite (default)
- Frontend: HTML, CSS
- Version Control: Git & GitHub

## Project Structure
project/

│

├── manage.py

├── db.sqlite3

├── school/

│ ├── models.py

│ ├── views.py

│ ├── templates/

│ ├── services/

│ └── tests.py

## Installation

1. Clone the repository:
```
git clone https://github.com/z00xINe/School-Task-by-Django.git
cd School-Task-by-Django
```
2. Create a virtual environment:
```
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Run migrations:
```
python manage.py migrate
```
5. Run server:
```
python manage.py runserver
```
6. Open in browser:
```
http://127.0.0.1:8000/
```
