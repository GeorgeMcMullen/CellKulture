# CellKulture

Track Your Cell and Tissue Cultures. CellKulture tracks cell cultures from the day they enter the lab to the day they leave. 

[More details](https://drdavidpier.github.io/CellKulture/index.html)

## Installation

1. Use your SQL management tool to run the SQL DB file located in the /app/db/ folder. If you're using a different name for your database or a table prefix, you will need to edit the SQL file to change the database and table names.
2. Place the app folder into an accessible area on your server. You may or may not need to include the .htaccess file, which contains additions for mod_rewrite for PHP. You may also need to update app/application/config/database.php and app/application/models/cold_model.php.
3. navigate to https://[YOUR-SERVER]/[BASE-FOLDER]/app/
4. Login with username: admin@gmail.com and password: admin
5. Done

Also note that this product also includes a reference to Google Analytics, which has been commented out. You may wish to uncomment it and change the analytics ID to your own by editing app/application/views/layouts/default.php.

###### Optional

6. To enable emails create a free account with sendgrid and enter details in the relevant controllers

### Need to use this in your lab without using a server? 

1. Download [this](http://www.usbwebserver.net/en/) and put it either in a folder on your computer or on a thumb drive
2. Open up phpmyadmin and import the SQL file
3. copy the app folder in to the root folder
4. navigate to localhost:8080/app
5. Done

