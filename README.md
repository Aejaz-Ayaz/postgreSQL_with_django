# postgreSQL_with_django

django comes with SQLite by default

I have added the settings.py, under "DATABASES" section you need to update. 

Finally run:

python manage.py makemigrations

python manage.py migrate

python manage.py runserver


If the server launches it means the database was successfully connected to postgres. 
