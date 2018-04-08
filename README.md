# Python Django RESTFul

# Prerequisition
## Virtual environtment
Virtual environtment let project to know which version of the project is.
```sh
pip install virtualenv
virtualenv -p /usr/local/bin/python3 env
source env/bin/activate
```

## Django
```sh
pip install django
```

## Django rest framework
```sh
pip install djangorestframework
```

## Core API
[http://www.coreapi.org/](http://www.coreapi.org/)
```sh
pip install coreapi
```

# Create project
```sh
django-admin startproject auth_api
```

# Create App
```sh
python manage.py startapp users
python manage.py startapp todos
```

# Project structure
```
.
├── README.md
└── auth_api
    ├── auth_api
    ├── manage.py
    ├── todos
    └── users
```
# Implementation Steps
```
1. Create routing for auth_api/urls.py
2. Create view auth_api/views.py

3. Create routing for todos/urls.py
4. Create routing for users/urls.py
```