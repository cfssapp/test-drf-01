# test-drf-01

py -3 -m venv venv 

venv\Scripts\activate

pip install djangorestframework

django-admin startproject todo_drf

cd todo_drf

django-admin startapp api

python manage.py runserver

python manage.py makemigrations

python manage.py migrate

python manage.py createsuperuser --email admin@example.com --username admin