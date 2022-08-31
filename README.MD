# VENV

## Check Python version
python --version

## Create a virtual environment
python -m venv ./venv 

## Go into/activate the venv
./venv/Scripts/Activate.ps1

## Deactivate venv
deactivate

# DJANGO

## Check libraries in environment
pip freeze
pip.main(['install', 'lib']) or pip install lib

## Check DJANGO commands
django-admin help

## Init project
pip install django
django-admin startproject name(btre)

## Run app
python manage.py runserver

## Create new app
python manage.py startapp pages 

## Copy static files
python manage.py collectstatic