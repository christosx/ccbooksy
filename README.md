# ccbooksy
CCBooksy - A light and nimble appointments booking webapp. Designed for barber shops.

Application Name: CCBooksy
Version: 1.1
License: MIT License
Copyrights: christoschristoforou.com
Database Name: booksy

CCBooksy is a light and nimble PHP plugin software for booking appointments designed and developed mainly for barbershops.
To install this PHP plugin create a database named "booksy". Then add the folder named "booksy" to your website's public folder. Then edit the functions.php file and define DBUSER and DBPASS. 
To access the admin panel add "/booksy/admin" next to your domain url. e.g. "domain.com/booksy/admin".
Register for the first time as administrator then login to the admin panel and go to SETTINGS. There you can setup your app settings according to your shop's needs.

For online use add ssl certificate to your website.

If you are using a VPS(Virtual Private Server) remember to set session.gc_maxlifetime bigger than 2592000 (bigger than one month) in your server's php.ini file. 

Live Demo: https://christoschristoforou.com/booksy
