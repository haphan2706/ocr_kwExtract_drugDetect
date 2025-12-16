#git clone


*Run terminal as administrator needed*

*Create virtual environment*


#Windows

python -m venv venv

venv\Scripts\activate


#MacOS/Linux

python3 -m venv venv

source venv/bin/activate


*Install sub-libs*

pip install -r requirements.txt


*Migrate one time only*

python manage.py migrate


*Run server*

python manage.py runserver

Server deploy at http://127.0.0.1:8000/..
