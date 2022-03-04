# contactapp
contactapp for ZOHO 
Python Django is used for creating this project.
Open the project in Pycharm or any other software,


Here "contact" is our projectname
and "contactapp" is our appname

--> RUN XXAMP and START APACHE AND MYSQL
--> CREATE A DATABASE IN MYSQL NAMED "contactapp"

DATABASE CONFIGURATION (XXAMP--)
Database = Mysql (changed database congfiguration in "contact/settings.phy")(default database is mysqlites3)
----------------------
DATABASES = {
    .default' : {
        'ENGINE': 'django.db.backends.mysql',
        'NAME ' : 'contactapp',
        'USER'  : 'root'
        'PASSWORD': '',
        'HOST':'localhost', # Or an IP Adress that yourDB is hosted on 
        'PORT': '3306',
        }
}
-----------------------
DatabaseName = contactapp
Table_Name = contacts


>python manage.py makemigrations 
>python manage.py migrate


Templates belongs to "Templates"Directory
{
homepage.html = HomePage
signin.html = LoginPage
signup.html = Registration






DATABASE CONFIGURATION (XXAMP..)
Database = Mysql (changed database configuraton in "contacts/settings
========================
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'contactapp',
        'USER': 'root',
        'PASSWORD':' ' , 
        'HOST':'localhost', # Or an IP Adress the
        'PORT': '3306'
        }
 }
 ======================
 DatabaseName = contactapp
 Table_Name = contacts
 
 
 AFTER CREATIN DATA BASE IN MYSQL,open terminal
 --->python manage.py makemigrations
 --->python manage.py migrate
 
 
 Templates belongs to "Templates" Directory
 {
 homepage.html = HomePage
 signin.html= LoginPage
 signup.html = Registration 
 }
 CSS files belong to  "contactapp/static/css/<css_files>"
 
 -->To run Project
 >Python manage.Py runserver
