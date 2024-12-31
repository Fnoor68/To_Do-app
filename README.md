# TO_DO_App_for_EDGE

This folder contains project code for step-by-step project for building a to-do app with Django.

## Setup Instructions

Command prompt codes:
 
python -m venv venv

.\venv\Scripts\activate

python -m pip install Django

python -m pip freeze > requirements.txt

django-admin startproject todo_project

python manage.py makemigrations todo_app

python manage.py migrate

python manage.py createsuperuser (User and Password should be provided)

python manage.py runserver
