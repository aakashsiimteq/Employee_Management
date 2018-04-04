## Please follow the following steps to setup the project.

### To set project up for virtual host
```
1.
<VirtualHost *:80>
    DocumentRoot "C:\xampp\htdocs"
    ServerName localhost
</VirtualHost>

<VirtualHost *:80>
    DocumentRoot "C:\Users\wolfenstein\Documents\GitHub\Employee_Management\public"
    ServerName employee.dev.project
</VirtualHost>

2.
127.0.0.1 localhost
127.0.0.1 employee.dev.project

3.
run the command
php artisan serve --host 0.0.0.0 --port 80
```
