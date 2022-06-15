# Study django for mac
start django
venv setting
```
brew install python3

python3 -m venv venvName

source venvName/bin/activate
pip install --upgrade pip
pip install django

django-admin startproject projectname
python3 manage.py runserver
```

make app
```
python3 manage.py startapp appName
```

make models

```
python3 manage.py makemigrations polls
python3 manage.py migrate
```

make admin
```
python3 manage.py createsuperuser
Username: admin
Email address: admin@example.com
Password: *********
Password (again): *********
Superuser created successfully
```