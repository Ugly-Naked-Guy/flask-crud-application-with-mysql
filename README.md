# flask-crud-application-with-mysql
This is a python flask crud application development 

## local development enviroment setup
To run the demo framework successfully in local computers. Please follow the follow the following steps including setting up MySql and Flask environments, configuring the Mysql server, importing demo-database into project folder, and etc. 

### Step1 
Install python and MySQL on your machine

### Step2
Go to terminal and install some relevant packages

    pip3 install flask
    pip3 install flask_mysqldb

### Step3 
You can either import the dataset into MySQL by

- installing MySQLWorkbench and using GUI 
![](https://paper-attachments.dropbox.com/s_8FAC4FB9CCE959A552D0F02E5B31F79A253F8478393075D30983A037BA96ED52_1595217144730_image.png)

- or using the following cmd

    ```
    // mysqladmin -u root password 'yourpassword'
    // mysql –u root –p
    mysql -uroot -p crud > crud.sql
    
### Step 4 
Open your project in IDE (for example, VS Code) and start working!

### Step 5
go to termial and `cd` to your work dirctory:

    python3 __init__.py
    
## Remote server setup:

We also tried to set up the server remotely using C-Panel. 
(URL: http://gameofthread.web.illinois.edu/UIUC_COVID19) 

![](https://lh4.googleusercontent.com/NZJA3GYhX6MO7MHRwRNO_U0QTXYlu27NV0_7IMXALXsC5mfOMSklTHqUMd5A-WFuQy0_NSpvELoWP0udiVX6sidW9C5uzEfyComEKjr3lKUdQ5sl67wmOifq58kUPqxwKAaj7LA)

The detailed steps shows as follow, 
 
### Step1
Register a domain in University of Illinois cPanel Web Hosting Service

![](https://lh4.googleusercontent.com/aegaEBEMDHePbvaCNgkOc-rD6NLbyBXD06L67yvqf3oyKS_lksCZTQwaUnJ_OK3qsrfOA2WvbaGQWp_iwK_1Li2KSqTKrJFmZPKiP6cUiWlpMF6dHLzH-2_uJzrAgFiBXe9aII8)

### Step 2
Create Python application in cPanel
 
![](https://lh3.googleusercontent.com/A5I0DJfindWMx6TtOThFowdMFV_soczNLk3lAlvYYIAFtCh7VwXeLSrTwN3MaPkZrbbrK6-Ih9ddMX9LvoV1D8PZU3df6hZRKDnopbXqM6ZsxR0KsBz8SLpezByq7W-74xYQ7F4)

Notes: The tutorial we follow for deploying flask application at cPanel is at https://www.youtube.com/watch?v=xFxL7Mvut6g
### Step 3
Upload files to File Manager’

### Step 4
Create database and add user
Notes: We follow the tutorial here https://www.youtube.com/watch?v=CHwxXGPnw48
  
## Remote database setup:

1. We use MySQL as our relational database.
2. To Import real data, we first create databases and users with MySQL® Database Wizard provided by cPanel, and then import data with phpMyAdmin provided by cPanel. 

