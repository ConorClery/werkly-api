# werkly-backend
Sample todo-list app, user creation of two different types (though i think it needs redoing)

## Installation
Alright boyos, you will need python3, pip3 and virtualenv to get going.

On first run you need to...
```sh
mkdir <project-name>
cd <project-name>
virtualenv venv
source venv/bin/activate
pip3 install django
pip3 install djangorestframework
git clone https://github.com/ConorClery/werkly-api
cd valuation-backend
python3 manage.py makemigrations
python3 manage.py migrate --run-syncdb
```
## General Project Dev
```sh
cd <project-name>
source venv/bin/activate
cd <repo-clone>
python3 manage.py runserver
```
