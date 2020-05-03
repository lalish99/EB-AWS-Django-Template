# Django 3.0 template for AWS Bean Stalk
----

# Features
* Custom User Model
* Lean deployement on AWS Bean Stalk


# How to use:
* Create a virtual environment *I suggest using (virtualenv)[https://pypi.org/project/virtualenv/]*
* Install requirements: `$ pip install -r requirements.txt`
* Move to the project directory: `$ cd backend`
* Migrate in order to setup the custom user model: `$ ./manage.py migrate`
* Test the installation by running the server: `$ ./manage.py runserver`
