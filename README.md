Run app as 
#### One time set up
 psql
create database listings;
\c listings;
create table listings;


source start-script
python save-to-db.py '{}'
#### Run webapp
python manage.py runserver
