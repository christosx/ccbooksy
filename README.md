# ccbooksy
CCBooksy - A light and nimble appointments booking webapp. Designed for barber shops.

Application Name: CCBooksy
Version: 1.0
License: MIT License
Copyrights: christoschristoforou.com
Database Name: booksy

CCBooksy is a light and nimble PHP plugin software for booking appointments designed and developed mainly for barbershops.
To install this PHP plugin create a database named "booksy". Then add the folder named "booksy" to your website's public folder. Then edit the functions.php file and define DBUSER and DBPASS. 
To access the admin panel add "/booksy/admin" next to your domain url. e.x. "domain.com/booksy/admin".
Register for the first time as administartor then login to the admin panel and go to SETTINGS. There you can setup your app settings according to your shop's needs.

For online use edit the admin/set_session.php file and set $secure to "true". This requirement is only for secure online websites that utilizes ssl certificate. For localhost conection leave it as "false".
