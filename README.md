# SE-Hands-On-lecture
Install Mysql &amp; Workbench

## Install MySQL on macOS ===================================
This procedure explains how to install [MySQL](https://www.mysql.com) using [Homebrew](http://brew.sh) on macOS

### Install Homebrew
* Installing Homebrew is effortless, open Terminal and enter :  
 `$  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
* **Note:** Homebrew will download and install Command Line Tools for Xcode 8.0 as part of the installation process.

### Install MySQL

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

