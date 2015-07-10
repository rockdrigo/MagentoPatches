Installed:
All selected repositories
Percona 5.6 .latest
PHP 5.5 .latest (with php: -opcache, -redis, -memcache, -igbinary)
Nginx .latest (mainline)
Memcached .latest
Redis .latest
Varnish 3 .latest
Magento 1.9.2.0 .latest

Additional:
phpMyAdmin 4.latest - advanced database management
mysqltuner.pl - database tuning script
MagenX default my.cnf for Percona

Configuration:
Optimizes php.ini, fastcgi_params, memcached, sysctl
php-fpm = ondemand
Nginx config for your domain
Mysql root and user passwords
mysql_secure_installation
Create database
Install Magento
Permissions
Magento cron
opcache invalidation
Magento Redis Cache backend
Magento memcache sessions
Creates new sudo user
PermitRootLogin no
Changes SSH default port
CSF firewall
Turpentine Varnish FPC

this script was tested on 4gb digitalocean droplet many times, works without any errors.

Rodrigo--
Probado en microsoft azure en maquina A2 con SO "basado en centos OpenLogic 6.5"
** no me funciono en centos 6.6 ni 7 
