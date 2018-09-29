# WebProduction
BrowsingBooks
#Requirements
1. XAMPP for PHP 7.0 and higher (Apache and MySQL)
2. Git bash
3. Composer for php
#Installation 
1. Setup and install XAMPP
2. Setup and install Git
3. Setup and install composer
4. copy project folder to directory "xampp/htdocs/"
5. open .env file and check database name
6. create database with same name in mysql
6. open git bash under project root folder and enter following commands
7. enter "composer update"
8. enter "php artisan key:generate"
9. enter "php artisan cache:clear"
10. enter "php artisan migrate:fresh"
11. enter "php artisan db:seed"
11. open browser and enter url "localhost/browsing/public/"
#Admin Account
username - admin@gmail.com
password - 123456
#Database Backup & Restore Data
1. Create new database with same collation (utf8mb4_unicode_ci)
2. Create database with same name in mysql (browsings)
3. Select the new database from the left navigation pane. In the resulting page, select the "Import" command in the top navigation bar. 
4. Click the "Browse…" button and select the backup file created earlier. Click "Go" to proceed.
5. phpMyAdmin will import the data from the backup file.
*****
First add the new categories when u need to add a new book. U will not need categories when already have its categories types
