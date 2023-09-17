# ci-taskmanager-1
First attempt at Flask task manager

## Setup
- Create new Repo
- Clone repo and create new project
- Open project in IDE
- Run cmd (for specific version): pip3 install 'Flask-SQLAlchemy<3' psycopg2 sqlalchemy==1.4.46
- Run cmd (for environment variables): touch env.py
- Run cmd (to ignore pushing ceratin files to github): touch .gitgnore
- Add env.py to .gitgnore
- Push to github

## Setup environment variables
- import os (the add 6 blank env variables - os.environ.setdefault("",""))
- assign the values required to the variables (IP, PORT, SECRET_KEY, DEBUG, DEVELOPMENT, DB_URL)
- Push to github

## Create python package 'taskmanager'
- Run cmd: mkdir taskmanager
- Inside 'taskmanager' 
- Run cmd: touch __init__.py
- Setup __init__.py
- Push to github

## Setup routes.py
- from flask import render_template
- from taskmanager import app, db
- create first route "/" and for now return base.html template

## Create run.py
- In project root directory create run.py
- Add file data

## Create templates (in taskmanager app)
- Create base.html
- Test app by running run.py (python run.py)
- Push to github