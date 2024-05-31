Adjust for different servers:

.htaccess
Replace the "api" in "RewriteRule ^(.*)$ /api/index.php?path=$1 [NC,L,QSA]" with the current path of the app

env.php
Adjust all variables in this file


Create database
- manually create an sql database named as DB_NAME defined in env.php
- call service/migrate 

***************

Create new app:
Create new database, 
setup env.php
Adjust .htdocs path

Define model
Define routes