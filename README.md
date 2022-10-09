# Django command blueprint
Below are the most common django commands for memorization. Note, if youre using a bash terminal (Mac or Linux), use ```python3``` anywhere you see ```python```

## Create Django project
```bash
django-admin startproject <project-name>
```

All other commands must be ran in the folder containing the ```manage.py``` file
```bash
cd <project-name>
```

## Run Django project
```bash
python manage.py runserver
```

## Create a Django App
```bash
python manage.py startapp <app-name>
```

## Make migrations and migrate models to database
```bash
python manage.py makemigrations
python manage.py migrate
```

## Open a shell in the project
```bash
python manage.py shell
```

## Create super user
```bash
python manage.py createsuperuser
```
