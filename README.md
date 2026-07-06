
# Laravel Websockets 
## by using LEMP (Linux, Nginx, MySQL, PHP)

### I build i project with Laravel +Websockets and i got to explain how to do that :
1-Configuring Laravel for Websockets.<br />
2-Setting up Comments API & AJAX.
3- Handling Socket Server Events.
4-Authenticating Private Channels.

------------------

Some code tips :
```
Sudo apt-get install nginx
sudo apt-get install mysql server
sudo mysql-secure-installation
```
```
sudo apt-get install php-fpm
sudo apt-get install php-mysql
sudo apt-get install php-mbstring
```
```
sudo nano /etc/php/7.0/fpm/php.ini
```

configure nginx
1-index
2-server-name
3-location

```
sudo nano /etc/nginx/sites-available/default
```


create a floder for laravel:
```
sudo mkdir -p /var/www/laravel
```
and we need to make a storage  Swap File
