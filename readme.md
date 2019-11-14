# Recipe API

[![Build Status](https://travis-ci.com/Raysultan/recipe-app-api.svg?branch=master)](https://travis-ci.com/Raysultan/recipe-app-api)

### About

Fully functional backend-API for a basic recipe application.

### Technologies

- Docker 19.03.4
- docker-compose 1.23.2
- Python 3.7.4
- Django 2.1.3
- django-rest-framework 3.9.0

### Features

- Authentication (Token based).
- User (Create, Retrieve, Update, List).
- Recipes (Create, Retrieve, Update, Delete, List).
- Ingredients (Create, Retrieve, Update, Delete, List).
- Tags (Create, Retrieve, Update, Delete, List).
- Filtering recipes based on tag or ingredient.

### How to start using?

In order to use you have to have required technologies installed (Listed above).

### Run server

Run the following commands in Terminal:
```bash
docker-compose build
docker-compose up
```

Now you can make requests to: http://127.0.0.1:8000/

License
----

MIT