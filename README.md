```bash
# Create a new Django project
django-admin startproject mysite

# Create a new app named 'blog'
python3 manage.py startapp blog

# Apply initial migrations
python3 manage.py migrate

# Create migrations for the 'blog' app
python3 manage.py makemigrations blog

# Show the SQL for migration 0001 of the 'blog' app
python3 manage.py sqlmigrate blog 0001

# Run the development server
python3 manage.py runserver

# Run the server on a specific IP and port with a custom settings module
python3 manage.py runserver 127.0.0.1:8001 --settings=mysite.settings

# Open the Django interactive shell
python3 manage.py shell

# Create a superuser for the Django admin panel
python3 manage.py createsuperuser
