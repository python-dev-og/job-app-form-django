## Create the project and application folders
```
django-admin startproject mysite .
python manage.py startapp job_application
```
## Connect the Application 

connect the application `job_application` to the project folder `mysite`'
Add `job_application` to the  INSTALLED_APPS [] block in the `mysite/settings.py`
 
## To run the application

```commandline
python manage.py runserver
```
## Design the database Model

Enter the database models on `job_application/models.py`

```commandline
 python manage.py makemigrations
 python manage.py migrate
```

## Create Views for our Models

create class in `job_application/views.py`

create `templates` in the `job_application` folder

create html file in `job_application/templates/index.html`
create html file in `job_application/templates/menu_item_detail.html`


create urls file in `job_application/urls.py`
create class file in `job_application/forms.py`

## Register our app with mysite 

In `mysite/urls.py`

add `path('', include('job_application.urls'))` to the urlpatterns

## Create a user for the admin page
```commandline
python manage.py createsuperuser
```
follow the prompt 