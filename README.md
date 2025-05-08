## Management commands used in this chapter

To create the file structure for a new Django project named mysite, we used the following command:
```python
django-admin startproject mysite
```

To create the file structure for a new Django application named blog:
```python
python manage.py startapp blog
```

To apply all database migrations:
```python
python manage.py migrate
```

To create migrations for the models of the blog applications:
```python
python manage.py makemigrations blog
```

To view the SQL statements that will be executed with the first migration of the blog application:
```python
python manage.py sqlmigrate blog 0001
```

To run the Django development server:
```python
python manage.py runserver
```

To run the development server specifying host/port and settings file:
```python
python manage.py runserver 127.0.0.1:8001 --settings=mysite.settings
```

To run the Django shell:
```python
python manage.py shell
```

To create a superuser using the Django authentication framework:
```python
python manage.py createsuperuser
```

For the full list of available management commands, check out https://docs.djangoproject.com/en/5.0/ref/django-admin/.