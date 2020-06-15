# django_webapp

##This is the web app I created for django practice.


## you will need python compiler installed on you machine and django library installed.
## once you have python on your machine run following command to download and install the libraries required to run the framework.

pip install django
pip install django-crispy-forms
pip install Pillow


##Now you should be good to run the server.
##To run the server go to command prompt navigate to the directory django_webapp and run the command :

python manage.py runserver

## By default your server will be running on http://localhost:8000/ or http://127.0.0.1:8000/
## If you want to run it on perticular IP and port than specify those after runserver
## If you want to run your server on different port runfollowing code:

python manage.py runserver 0.0.0.0:8888

## If you want to make the server accessible to all the machines on local network than you will need to run the server on the local IP
## you can find that local ip by opening new command window and passing command "ipconfig" and then go to LAN adapter Local Area Connection and copu the IPv4 ip address and then run the server on that IP and port 8000 with following command..

python manage.py runserver 192.XXX.XX.XX:8000