Virtualization Environment
Creates the environment (a folder in your current directory)

> virtualenv env

> env\scripts\activate

Command(s)

> python manage.py runserver

> python manage.py createmigrations
> python manage.py migrate

> python manage.py createsuperuser

Installing RESTFRAMEWORK

> pip install djangorestframework

add 'rest_framework' to your INSTALLED_APPS setting. INSTALLED_APPS = [ ... 'rest_framework', ]
