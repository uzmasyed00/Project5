# Project5

IP address: 54.69.10.80
ssh port:2200

Complete url: http://54.69.10.80

Here are the list of packages that I installed:
sqlchemy
Flask-SQLAlchemy
python-psycopg2
postgresql
apache2
libapache2-mod-wsgi

Steps to run the application:

Paste the given udacity_rsa.key into a text editor and save into .ssh directory on your machine.
Navigate to the .ssh directory and type the following:

ssh grader@54.69.10.80 -p 2200

Once inside the server, run the following command:

sudo service apache2 restart

In a browser of your choice, navigate to http://54.69.10.80 and you will see the Item Catalog application running.




