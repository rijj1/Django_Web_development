# Django Web development
Step to start Developing Using Django

### 1. Enable Virtual Environment
First run the below command to make a virtual environment
````bash
pip install virtualenv
python3 virtualenv venv
````

Then run this to activate the Virtual Environment
````bash
source venv/bin/activate
````

### 2. Install Django package
Use the command to install django in the virtual environment
````bash
pip install django
````

### 3. Create a Django project
To create a new project with name django_project, run the following command:
````bash
django-admin createproject django_project
cd django_project
````
To run the webserver just run the following command:
````bash
python3 manage.py runserver
````