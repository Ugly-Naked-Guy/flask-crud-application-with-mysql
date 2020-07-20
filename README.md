# flask-crud-application-with-mysql
This is a python flask crud application development 

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

