# Introduced with following commands

django-admin startproject mysite
python3 manage.py startapp blog
python3 manage.py migrate
python3 manage.py makemigrations blog
python3 manage.py sqlmigrate blog 0001
python3 manage.py runserver
python3 manage.py runserver 127.0.0.1:8001 --settings=mysite.settings
python3 manage.py shell
python3 manage.py createsuperuser
