```
django-admin startproject mysite .
python manage.py startapp job_application
```

Add 'job_application' to the  INSTALLED_APPS [] block in the "mysite/settings.py"
 
## To run the application
```commandline
python manage.py runserver
```
## Setup the database 

Enter models on job_application/models.py

```commandline
 python manage.py makemigrations
 python manage.py migrate
```

create class in job_application/views.py

create html file in job_application/templates/index.html
create urls file in job_application/urls.py



