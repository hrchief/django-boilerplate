# Setup a new Django project

```py --version```

```py -m venv swim-gym-backend```

```swim-gym-backend\Scripts\activate.bat```

```py -m pip install Django```

```django-admin startproject SwimGym```

```python manage.py startapp User```

# Integration with MySQL

```
DATABASES = {  
  'default': {  
    'ENGINE': 'django.db.backends.mysql',  
    'NAME': 'Blog',  
    'USER':'root',  
    'PASSWORD':'',  
    'HOST':'localhost',  
    'PORT':'3306'  
  }
```