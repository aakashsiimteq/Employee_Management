## Please follow the following steps to setup the project.

### To set project up for virtual host
```
1. Make changes to your apache configuration File in the xampp folder : C:\xampp\apache\conf\extra\httpd-vhosts
<VirtualHost *:80>
    DocumentRoot "C:\xampp\htdocs"
    ServerName localhost
</VirtualHost>

<VirtualHost *:80>
    DocumentRoot "Your Project Path"
    ServerName employee.dev.project
</VirtualHost>

2.Make changes to your Hosts file located in : C:\Windows\System32\drivers\etc\hosts
127.0.0.1 localhost
127.0.0.1 employee.dev.project

3.
run the command
php artisan serve --host 0.0.0.0 --port 80
```
