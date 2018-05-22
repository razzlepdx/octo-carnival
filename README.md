# Octo-Carnival - A Django and TDD Practice Project

## Goals for this project:

    - 1 model - a movies table that stores a movie title
    - 1 view - a template that contains the following:

        - title and header that indicate this is an app to make a movie list
        - an input box with placeholder to prompt users to add a movie title
        - a button that handles creating a Movie object with the user input
        - a list that displays either all the movies currently entered, or a
        a message that alerts that user that no movies have been added yet.
        - the movies list should be persistent since its contents come from the
        database.
    - functional and unit tests with at least 50% test coverage

## Technology used:

    - Python 3.6
    - Django 2.0
    - Selenium 3
    - Javascript
    - HTML/CSS
    - Postgres
    
## Setting up your development environment for local testing

    - Ensure dependencies are available (activate environment as necessary)
    - clone the repository
    - change to the directory with manage.py in it
    - run `python manage.py migrate` to create database tables
    - run `python manage.py runserver`
    - open browser to http://localhost:8000/movies
    - to run all tests: `python manage.py test`
    - to run unit tests only: `python manage.py test movies`
