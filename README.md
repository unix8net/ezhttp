Description
===========
ezhttp is a powerful bash script for the installation of web server(Apache,Nginx,PHP,MySQL and etc).You can install Apache Nginx PHP MySQL in an very easy way,Just need to input numbers to choose what you want to install before installation.And all things will be done in a few minutes.

Supported System
===============
* CentOS-5.x
* CentOS-6.x
* CentOS-7.x
* Ubuntu-12.04
* Ubuntu-14.04
* Debian-6.x
* Debian-7.x
* Other Linux Distribution

Supported Software
==================
* Nginx OpenResty Tengine
* Nginx Module: lua_nginx_module nginx_concat_module nginx_upload_module ngx_substitutions_filter_module
* Apache-2.2 Apache-2.4
* MySQL-5.1 MySQL-5.5 MySQL-5.6 MySQL-5.7
* PHP-5.2 PHP-5.3 PHP-5.4 PHP-5.5
* PHP Module: ZendOptimizer ZendGuardLoader Xcache Eaccelerator Imagemagick IonCube Memcache Memcached Redis Mongo Xdebug Mssql
* Other Software: Memcached PureFtpd PhpMyAdmin Redis Mongodb PhpRedisAdmin MemAdmin RockMongo Jdk7 Jdk8 Tomcat7 Tomcat8

Useful Tools
============
* System_swap_settings - setup swap automatic
* Generate_mysql_my_cnf - generate mysql my.cnf configuration file according your server memory and other option you set.
* Create_rpm_package - package your software with rpm tool.
* Percona_xtrabackup_install - install xtrabackup.Helpful when need to backup the MySQL data.
* Change_sshd_port - change your sshd port automatic
* Iptables_settings - setup iptables in an easy way
* Enable_disable_php_extension - manage your PHP extensions
* Set_timezone_and_sync_time - setup system timezone and synchronize time with ntp
* Initialize_mysql_server - initialize mysql server data
* Add_chroot_shell_user - create a linux system user with a chroot home directory
* Network_analysis - this tool is definitely helpful when you need to know your network status.
* Backup_setup - powerful backup tool.

Installation
============
```bash
wget  https://github.com/centos-bz/ezhttp/archive/master.zip?time=$(date +%s) -O ezhttp.zip
unzip ezhttp.zip
cd ezhttp-master
chmod +x start.sh
./start.sh
```
Bugs & Issues
=============
Please feel free to report any bugs and issues to me, my email is: admin@centos.bz.
中文支持:https://www.lxconfig.com/forum-65-1.html