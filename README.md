# Django Authentication Project (PinkAuth)

This is a Django-based user authentication system with user registration, login, logout, and a protected dashboard. The UI is styled using Bootstrap 5 with a modern pink theme, centered forms, and mobile responsiveness.

## Features

- User registration with password validation  
- Login and logout functionality  
- Authenticated dashboard view  
- Clean, centered iOS-style form layout  
- CSRF protection and secure password hashing (default in Django)

## How to Set Up and Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/ddtbone1/django-auth-proj.git
cd django-auth-proj

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate

### 3. Install Dependencies

```bash
pip install django

### 4. Run Migrations

```bash
python manage.py migrate

### 5. Create a Superuser

```bash
python manage.py createsuperuser

### 6. Run the Development Server

```bash

python manage.py runserver
