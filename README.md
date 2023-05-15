# Django-REST-framework-tutorial

## Installation

Install using `pip`...

    pip install django
    pip install djangorestframework
   
Add `'rest_framework'` to your `INSTALLED_APPS` setting.
```python 
INSTALLED_APPS = [
  ...
  'rest_framework',
]
```

## Execution method

    python manage.py ruserver

## Composition of files in the repository

<pre>
.
├── Django_REST_framework_tutorial
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-310.pyc
│   │   ├── settings.cpython-310.pyc
│   │   └── urls.cpython-310.pyc
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── README.md
├── db.sqlite3
├── manage.py
└── quickstart
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── migrations
    │   └── __init__.py
    ├── models.py
    ├── serializers.py
    ├── tests.py
    └── views.py
</pre>
