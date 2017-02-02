# Linux Web Development Environment

This article helps you get started with setting up a web developing environment and tools.
  - apache2
  - php5.6
  - mysql-server
  - composer
  - 
  
**Installing apache**
```sh
$ sudo apt-get install apache2
```
you will be shown a list of the packages that will be installed, along with the amount of disk space they'll take up. Enter Y to continue.

**Installing php5.6**
php5.6 in ubuntu 16.04
```sh
$ sudo add-apt-repository ppa:ondrej/php
$ sudo apt-get update
$ sudo apt-get install php5.6
$ sudo apt-get install php5.6-mbstring php5.6-mcrypt php5.6-mysql php5.6-xml php5.6-curl
```
**Installing mysql**
```sh
$ sudo apt-get install mysql-server
```
during the installation you have to set the password for the root user of mysql

**Installing composer**
```sh
$ curl -sS https://getcomposer.org/installer | php
```
to use composer [globally]
```sh
$ sudo mv composer.phar /usr/local/bin/composer
```

[globally]: <https://getcomposer.org/doc/00-intro.md#globally>
