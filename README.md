# djangoy-todos
A neat little todo list app

Uses Django 1.11 and MySql

Django Commands for generating/updating the DB:
===============================================
python manage.py makemigrate todos
python manage.py migrate
python manage.py loaddata todos_category.json --app todos

Django Command to run the server
================================
python manage.py runserver
