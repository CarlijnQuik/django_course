# Check Python version
python --version

# Create a virtual environment
python -m venv ./venv 

# Go into/activate the venv
./venv/Scripts/Activate.ps1

# Deactivate venv
deactivate

# Check libraries in environment
pip freeze

# Check DJANGO commands
django-admin help

# Init project
pip install django
django-admin startproject name(btre)

# Run app
python manage.py runserver