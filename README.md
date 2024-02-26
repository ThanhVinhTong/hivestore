# About hivestore project:
This is an ecommerce website for selling fashion stuffs in general such as clothes & shoes.

# Overview:
- This project is done utilizing PHP as the backend, HTML and CSS as the frontend, and MySQL as the database.
- I also implemented the MVC architecture to facilitate easier maintenance and scalability in the future.
- A glance at my website:
![alt text](https://github.com/ThanhVinhTong/hivestore/blob/main/hivestore_homepage.png?raw=true)

# Installation steps
To run this project, we will need to install a couple of things:
- php: https://www.php.net/downloads.php
- wamp: https://sourceforge.net/projects/wampserver/
- mysql workbench: https://dev.mysql.com/downloads/workbench/

Next, run the MySQL workbench and WAMP server, then create a schema named "hivestore". Following that, copy all sql scripts in the "hivestore_db_script.sql" file which is located in /hivestore/db/hivestore_db_script.sql, into the mysql workbench script to execute so that the website can have a database.

Lastly, move the project or the folder "hivestore" into the folder wamp's subfolder "wwww" (for example, the final result can be "C:/wamp64/www/hivestore").

After finishing all the above steps, the website can be accessed through the browser at "http://localhost/hivestore/".

# Note that: 
- The wamp server must be run in the background so that the website can be accessed!
