# producthunt_clone
A producthunt clone app for training purposes. Using Python, Django, and Postgresql.

## Creating a DB

Please, create a DB with the same settings \(name, username, password\) established by the team.

_name for the DB should be 'producthunt\_db', user: 'postgres','password': 'postgres123'_

## Creating a virtual environment

Create a virtual environment by running `pip install virtualenv`. Then if you pick a name like _myenv_, run `virtualenv myenv`

## Activating your virtual environment

If you are a Mac user, activate your environment by running `source myenv/bin/activate`  
If you are a Windows user, activate your environment by running `source myenv/Scripts/activate`

## Installing dependencies

After activating the environment, run `pip install -r requirements.txt` to install all dependencies needed for this project. 🍾

More about the _requirements.txt_ and _pip freeze_ can be found at: \([https://pip.pypa.io/en/stable/reference/pip\_freeze/](https://pip.pypa.io/en/stable/reference/pip_freeze/)\) 🎯

## Starting Django on your local server

So, a project was created with Django. The main project folder is called `producthunt`. Go to producthunt and run `python manage.py runserver`. If everything works correctly you should see a Welcome page by Django on: `http://127.0.0.1:8000/`

Remember to run `python manage.py migrate` to apply migrations.

_Important_: `django startproject` creates a root app folder for the project \(`producthunt`\). Inside, you can edit your settings. Your other apps will live inside the project, as 'sisters' of the 'crc' folder. Remember that if you want to commit anything or make changes to push to Git, you'll always have to go back to the parent folder which is where our repo lives \(`code-resource-center`\)

## Django Admin

To run the admin panel and make sure the DB is working fine, go to your root folder and run `python manage.py runserver`. Then, go to `localhost:8000/admin/`. Login with the superuser \('postgres'\) and password \('postgres123'\)

## Bootstrap

Check this documentation in order to add Boostrap to the project. \([https://pypi.org/project/django-bootstrap3/](https://pypi.org/project/django-bootstrap3/)\) For full documentation, check: \([https://django-bootstrap3.readthedocs.io/en/latest/](https://django-bootstrap3.readthedocs.io/en/latest/)\)

