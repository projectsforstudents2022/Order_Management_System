# Order_Management_System

## Run project, run the following commands in the project's directory to create the database. When running the software for the first time, it is necessary to run each command for each app in the project
```
python manage.py makemigrations homepage
python manage.py migrate homepage
python manage.py makemigrations inventory
python manage.py migrate inventory
python manage.py makemigrations transactions
python manage.py migrate transactions
```
## After the first time, the following can be run to migrate model changes in any app
```
python manage.py makemigrations
python manage.py migrate
```

## Use the following command to create an admin user 
```
python manage.py createsuperuser
```

## Use the following command to run the server
```
python manage.py runserver
```
## Outrput

![Screenshot](picture1.png)

![Screenshot](picture2.png)
