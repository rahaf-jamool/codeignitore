# **Requirements**

- PHP >= 7.4
- cURL PHP Extension
- Fileinfo PHP Extension
- Exif PHP Extension
- Mbstring PHP Extension

# **Installation**

## ENV
1. rename .env.example to .env
2. modify the app.baseURL in the .env file
3. > for debugging edit CI_ENVIRONMENT = production to CI_ENVIRONMENT = development

## Database
1. go to app > Config
2. rename Database.example.php to Database.php
3. modify the following in the Database.php:
- hostname
- username
- password
- database
4. download the database [here](https://nc.visuency.com/s/dC6rmyxGiBkk8mN)
5. import the downloaded sql file to your database
> if you do not have any tool like phpmyadmin, run the following script via Linux CLI. I made all my tests so far only on Debian 11.
```
mysql -h [hostName] -P [port] -u [userNmae] -p [databaseName] < [fileName.sql]
```
## Login

```
admin: admin@admin.admin
user: demo@demo.demo
password: Test123
```