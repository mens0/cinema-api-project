# Cinema-Service API
> Django-REST framework API for managing cinema-service

## Installing / Getting started

Python and PostgreSQL must be installed

```shell
git clone https://github.com/mens0/cinema-api-project.git
cd cinema_api_project
python -m venv venv
venv/scripts/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
python manage.py runserver
```

### Run using Docker

Docker should be installed


```shell
docker-compose build
docker-compose up
```

## Features

* Swagger Documentation
* JWT authentication
* Admin panel
* Managing orders and tickets
* Creating movies with genres, actors
* Creating cinema halls instances
* Adding movie sessions
* Filtering movies and movie sessions by title, genres, movies
* User and superuser functionality
