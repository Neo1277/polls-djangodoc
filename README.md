# Polls application Django #

Polls application from [Django documentation (tutorial)](https://docs.djangoproject.com/en/3.1/intro/tutorial01/ "djangotutorial")

## Installation ##
*   Create a virtual enviroment for the django dependencies [Link official documentation](https://docs.djangoproject.com/en/3.1/intro/contributing/#getting-a-copy-of-django-s-development-version "djangoenviroment")
*   Activate the enviroment and go to the polls-djangodoc folder and install the Django dependencies with the following command using the requirements.txt file which has the dependencies
	* ### `pip install -r requirements.txt`
*   To create the tables on the database, on the polls-djangodoc folder run the following commands (python or python3 depends on your configuration when the enviroment variable on the system was set up)
	* ### `python manage.py makemigrations`
	* ### `python manage.py migrate`

## How to run it ##
*   Go to the polls-djangodoc folder and run
	* ### `python manage.py runserver`