# Install requirements
python -m pip install -r requirements.txt

# create admin 
python manage.py createsuperuser

# make migration for changes 
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

# Port
http://127.0.0.1:8000/