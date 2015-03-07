# Deployment package for Hello Web App

Making sure your local database is the same format as your production database
is a highly recommended--however, it's a lot easier for beginning programmers to
develop locally using a SQLite3 databse, but deploying on Heroku requires 
PostgreSQL.

This package will install all the necessary packages for deploying a Django
project on Heroku, but will only install psycopg2 if PostgreSQL is installed on
the local computer.

Packages installed:
* gunicorn
* dj-database-url
* dj-static
* psycopg2 (only if PostgreSQL is installed.)
