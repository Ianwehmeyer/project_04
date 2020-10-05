# project_04

django-admin startproject week21
cd week21django-admin startapp example
code . (opens in visual studio)
python manage.py runserver

python manage.py makemigrations - only have to do when I change the model itself
python manage.py migrate
python manage.py shell

>>> from example.models import Account
>>> account = Account(total=100)
>>> account.save()
exit()

look up error code for is_valid() - per Larson that should be a good thing to add to website


pip install django-bootstrap4

pip install django-bootstrap-themes

*under installed apps add bootstrap info
INSTALLED_APPS = [
    'bootstrap4',
    'bootstrap_themes',
]

python manage.py runserver


refer to django module for building user + I believe Karl did a video. Double check. 