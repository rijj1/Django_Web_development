# Project 1: CAR LISTING PROJECT
<p>Here we would create a webpage using Django framework for listing cars. There would be login features and many more. Here first user need to register themselves and then login to create their car listing and also see the listing of the other users along with address and phone number</p>

## 1. Create Super User for the Admin Panel
To create a Super User for the Admin Panel use the command
````bash
python manage.py migrate
python3 manage.py createsuperuser
````

<p><b>My SuperUser Credentials</b><br>
    Username: admin<br>
    Password: 12345678<br></p><br>
    
If using in gitpod add this line in settings.py
````bash
SECURE_PROXY_SSL_HEADER = ('HTTP_X_FORWARDED_PROTO', 'https')
````
## 2. Create a new app
(a) For creating a new app name 'main', run the code
````bash
python3 manage.py startapp main
````
(b) Include the <b>main</b> app name in the car_listing settings.py inside INSTALLED_APPS
(c) Add the views and include it in the url.py file
(d) Done... You can now start developing the main app
