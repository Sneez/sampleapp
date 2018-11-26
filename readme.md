Eric's Sample Laravel App!

This is a very simple Laravel app I made to get started with learning Laravel.  You can
create messages in /contact and view a list of all the messages in /messages.

To run:

Download XAMPP, npm, composer

Run XAMPP and navigate to localhost/phpmyadmin

Create a password in phpmyadmin on browser, then set same password in xampp/phpmyadmin/config.inc file

Create a database in phpmyadmin on browser (I named mine 'basicwebsite')

Create file called .env in root of /sampleapp, same as .env.example file but change DB_DATABASE, DB_USERNAME, and DB_PASSWORD to your settings.

Clone this into xampp/htdocs/sampleapp

Run 'composer install', 'npm install', 'npm run dev'

Navigate to localhost/sampleapp/public