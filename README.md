# digital-ocean-challenge
Create a scalable MySQL Database Cluster Hosting Multiple Sites 
Requirements:-
- Windows Or Linux Server Installed With Either Apache Or Ngnix
- Digital Ocean Managed MySQL Database Cluster
- MySQL Workbench
- 


Create a scalable MySQL Database Cluster. On the same cluster, create another administrative user with MySQL Native Password Encryption 5+ legacy and save the following connection details regarding the cluster:- Username, Password, Host And The Port. 

Then Open MySQL Workbench and add the connection details. Make Sure You Test The Connection. Sometimes "db-mysql-nyc3-05157-do-user-8532287-0.b.db.ondigitalocean.com" shows that it's an invalid hostname but try to ping it and then use the ip address instead.

Then open the newly added user account using MySQL Workbench. Then Create a database where you are going to import the database file "database_to_import.sql". Make sure that you use MySQL Workbench to create the database and don't use the digital ocean dashboard because the database import may fail to work with errors.

There after import the database file into the newly created database by clicking Start Import And The Import Should Be Successful As Shown Below:-

Then head over to the location on your server where you uploaded the website files and open the admin/config.php file and set it as shown below and then save it:- 

Then head over to your browser and visit the url where your server is running and your newly created website should be up and running like shown below:- 

You can as well visit the admin panel http://127.0.0.1/testing/admin/login.php and start tuning and managing the website to your own desires.

Role          Email                  Password
Super Admin   sadmin@gmail.com       1234
Admin         admin@gmail.com        1234
Publisher     publisher@gmail.com    1234

In just ten minutes, you have a website up and running using the incredible digital ocean scalable MySQL Database Cluster 

The greatest benefit you will achieve using digital ocean's managed sql database cluster is:-
-It's high availability because the cluster can be configured to span across multiple data centers.
-Security Vault – Encryption at rest and in motion regardless of where it is used, moved or stored.
-Monitoring – Built-in the service.
