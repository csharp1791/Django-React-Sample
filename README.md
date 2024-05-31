echo "# Django-React-Sample" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:csharp1791/Django-React-Sample.git
git push -u origin main

--------------------------------

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

