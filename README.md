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
# Other tools
---

#### phpstrom
***Install dependencies***
```sh
$ sudo apt-get purge openjdk*
$ sudo add-apt-repository ppa:webupd8team/java
$ sudo apt-get update
$ sudo apt-get install oracle-java8-installer oracle-java8-set-default
```
***Install PhpStorm***
```sh
$ wget http://download-cf.jetbrains.com/webide/PhpStorm-10.0.2.tar.gz
$ tar -xvf PhpStorm-10.0.2.tar.gz
$ cd PhpStorm-143.1184.87/bin/
$ ./phpstorm.sh
```

#### sublime text 3
for 32bit use this link https://download.sublimetext.com/sublime-text_build-3126_i386.deb
```sh
$ wget https://download.sublimetext.com/sublime-text_build-3126_amd64.deb
$ sudo dpkg -i sublime-text_build-3126_amd64.deb
```



[globally]: <https://getcomposer.org/doc/00-intro.md#globally>
