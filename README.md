python3 -m venv env

source env/bin/activate

pip install django

django-admin startproject watchmate

cd watchmate

python3 manage.py startapp watchlist_app

python3 manage.py  makemigrations

python3 manage.py migrate

python3 manage.py createsuperuser

pip install djangorestframework

python3 manage.py runserver 8069

--------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/62cf6051-16f4-492b-8fe1-009924eac67a)

![image](https://github.com/user-attachments/assets/75827173-5c41-4ee0-a0cd-86cdf6fe7e3d)




