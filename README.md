python3 -m venv DjRT.env

source DjRT.env/bin/activate

pip3 install -r requirements.txt

django-admin startproject backend

cd backend

python3 manage.py startapp api

----------------

python3 manage.py makemigrations

python3 manage.py migrate

python3 manage.py runserver

