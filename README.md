# Base Applcation for Starting in Django

>Credit To https://simpleisbetterthancomplex.com/videos/2018/11/04/django-auth-video-tutorial.html 


### What is this

Django Based Auth Project for developing new Application which required authentication
>IT INCLUDE

>Registration

>Login

>Logout

>Change Password

>Reset Password (Local Email Based SMTP based not done)

>@login_required pages

### Requirements and Installation
Python 3.7
Django==3.0.8

>pip install django-crispy-forms

### How To Run the project
goto directory "mysite"
>python manage.py migrate. 

To test mail local
>python manage.py senttestmail test@testmail.com

To add User email manually "if user exist"
>python manage.py shell

>from django.contrib.auth.models import User

>a= User.objects.get(username="<username>")  

>a.email ="<username>@testmail.com"

>a.save()

>exit()

To Run server

>python manage.py runserver.

open 127.0.0.1:8000

