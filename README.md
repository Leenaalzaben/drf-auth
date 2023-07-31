# drf-auth

## LAB - Class 33 || Authentication & Production Server

### Author || LeeNa Alzaben

### Solution

1. create django project

- `django-admin startproject project-name .`

2. Create django application

- `python3 manage.py startapp app-name`

3. To run the server

- `python3 manage.py runserver`

4. Create a superuser with all permissions

- `python3 manage.py createsuperuser`

5. Make migrations

- `python3 manage.py makemigrations`
- `python3 manage.py migrate`

6. Command for Docker part 

- `docker-compose up`
- `docker-compose up --build`

- `docker-compose run web python3 manage.py migrate`
- `docker-compose run web python3 manage.py createsuperuser`
