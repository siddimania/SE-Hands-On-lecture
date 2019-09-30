## SE-Hands-On-lecture
Install Mysql &amp; Workbench

## Step 1. 
### 1.1 Install MySQL on macOS 
This procedure explains how to install [MySQL](https://www.mysql.com) using [Homebrew](http://brew.sh) on macOS

### 1.2 Install Homebrew
* Installing Homebrew is effortless, open Terminal and enter :  
 `$  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
* **Note:** Homebrew will download and install Command Line Tools for Xcode 8.0 as part of the installation process.

### 1.3 Install MySQL

* Enter the following command : `$ brew info mysql`  
* Expected output: **mysql: stable 8.0.17 (bottled)**

To install MySQL enter : `$ brew install mysql`
  
After the installation
* Expected output: *

```
To connect run:
    mysql -uroot

To have launchd start mysql now and restart at login:
  brew services start mysql
Or, if you don't want/need a background service you can just run:
  mysql.server start
```

### 1.4 Start MySQL Server

* Enter the following command : `$ mysql.server start`  
* Expected output: 
```
Starting MySQL
.. SUCCESS!

```

### 1.5 Setup Admin Password

* Enter the following command : `mysqladmin -u root password 'root'`  
* **Note:** I'm keeping it root for simplicity but you can use some other password as well.
* Expected output: 
```
mysqladmin: [Warning] Using a password on the command line interface can be insecure.
Warning: Since password will be sent to server in plain text, use ssl connection to ensure password safety.

```

### 1.6 Connect to Mysql 
* Enter the following command : `mysql -u root -p`  
* **Note:** It will prompt you to enter your password, just enter your password provided in the previous step.
* Expected output: 
```
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 11
Server version: 8.0.17 Homebrew

Copyright (c) 2000, 2019, Oracle and/or its affiliates. All rights reserved.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql>
mysql>

```


## Step 2. 
### 1.1 Install Workbench
[Download Link for Workbench](https://dev.mysql.com/downloads/workbench/)

* It will download the dmg file of workbench, just install it will default config
 
### 1.2 Follow the steps in the ppt to know More.
* Workbench PPT in repository
   
