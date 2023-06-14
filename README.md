mkdir django2

cd django2

code .

python3 -m venv .venv

. .venv/bin/activate

pip install django whitenoise gunicorn django-bootstrap4 PyMySQL django-stdimage

pip freeze > requirements.txt

django-admin startproject django2 .

django-admin startapp core

editar settings.py

=================================================================================
MySQL

CREATE DATABASE django2;
=================================================================================

editar core.views.py

criar pasta core.templates

criar contato.html index.html produto.html

criar pasta core.static

criar pastas: css, js, images

crair arquivo js.

editar urls.py

criar core.urls.py

Talvez:
sudo apt-get install libmysqlclient-dev python3-dev (root)
pip install MySQL (projeto)

pip freeze > requirements.txt

python manage.py makemigrations && python manage.py migrate

python manage.py createsuperuser

admin / email@email.com / 123456 / y

python manage.py runserver

editar admin.py

criar forms.py

================================================================= 

python manage.py shell

from django import forms

dir(forms)

help(forms.Charfield)

dir(forms.Form)

help(forms.Form.is_valid)

=================================================================

editar settings.py

pip freeze > requirements.txt

Publicar. (fazer alterações)