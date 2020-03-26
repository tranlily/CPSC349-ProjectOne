## Project One

Group members:

shijie feng - donfeng97@csu.fullerton.edu

ying wen- ywen1306@csu.fullerton.edu

shalom yemane - syemane@csu.fullerton.edu

lily tran - derpyhooves@csu.fullerton.edu

## Setup

Download Apache from [Download - The Apache HTTP Server Project](https://httpd.apache.org/download.cgi)


### `sudo apachectl start`
### `sudo nano /etc/apache2/httpd.conf `

You’ll need to remove # before LoadModule php5

### `sudo apachectl restart`
### `sudo nano /etc/apache2/httpd.conf`

Add index.php in DirectoryIndex line

### `sudo apachectl restart`


Download PHP from https://www.php.net/downloads

Download MySQL from [MySQL :: Download MySQL Community Server](https://dev.mysql.com/downloads/mysql/)

Choose the appropriate download for your system
Remember to save your password


### `sudo mkdir /var/mysql`
### `sudo ln -s /tmp/mysql.sock /var/mysql/mysql.sock`

Start your MySQL server

### `cd /usr/local/mysql/bin`
### `sudo ./mysql -u root -p`

Open localhost/phpMyAdmin/setup, set up a new server 
Download Config
Copy/Paste config into config folder
Create the database and tables accordingly

Download the project ZIP file
Unzip the folder

Move the folder to ~/Library/Documents/Webserver
Go to localhost/CPSC349-ProjectOne/register.php
