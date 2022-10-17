# How to run
```Scripts\activate.bat```

```py -m pip install -r requirements.txt```

# Setup a new Django project

```py --version```

```py -m venv swim-gym-backend```

```swim-gym-backend\Scripts\activate.bat```

```py -m pip install Django```

```django-admin startproject SwimGym```

```python manage.py startapp User```

# Integration with PostgreSQL

```
DATABASES = {
  'default': {
    'ENGINE': 'django.db.backends.postgresql',
    'NAME': env('DB_NAME'),
    'USER': env('DB_USER_NAME'),
    'PASSWORD': env('DB_USER_PASSWORD'),
    'HOST': env('DB_HOST'),
    'PORT': env('DB_PORT'),
  }
}
```

# Migrate the Database

py manage.py makemigrations

py manage.py migrate