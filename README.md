<div align="center">

# Discode

This app is a forum where people can create accounts and socialize with others by creating interactive posts. This social app was made as a way for me to better solidify my understanding of Django, Python, and CRUD operations.

</div>

#

## Libraries

```bash
Django
```

## Startup Procedure for New Project

```bash
python manage.py startapp base (creates app directory called base)
```

Go inside settings.py (not in base dir) and enter the following under INSTALLED_APPS.

```bash
'base.apps.BaseConfig',
```

Create models and migrate tables to SQLite

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```

## Installations

```bash
python
pip install django
pip install virtualenv
pip install -r requirements.txt
```

## Other Useful Commands

```bash
virtualenv [virtual_env_name]
/[virtual_env_name]/Scripts/activate
deactivate
django-admin
django-admin startproject [project_name]
python manage.py makemigrations
python manage.py migrate
```

## Run Application

```bash
python manage.py runserver
```

> ⚠ Then, the development server will be started at http://127.0.0.1:8000/
