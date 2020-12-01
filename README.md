# Python Planetary API

My source code after taking the Lynda.com course:
[Building RESTful APIs with Flask](https://www.lynda.com/Flask-tutorials/Building-RESTful-APIs-Flask/794143-2.html)

## Setup and run

1. Clone this repo and `cd` into it
1. `touch planets.sqlite`
1. `python3 -m pip install --user virtualenv`
1. `python3 -m venv env`

### Run the app

1. `source env/bin/activate`
1. `export FLASK_DEBUG=1 && export FLASK_APP=app.py`
1. `pip install -r requirements.txt`
1. `flask run`

Control + C will stop the web server.

### Seeding the database

1. `flask db_create`
1. `flask db_seed` will seed the database

When you are done with the virtualenv, use: `deactivate`.

## Updating the `requirements.txt` file

`pip freeze > requirements.txt`
