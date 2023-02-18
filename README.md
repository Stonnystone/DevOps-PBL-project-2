# DevOps-PBL-project-2
PROJECT 2: LEMP STACK IMPLEMENTATION 

This project will extend your knowledge of various Web Stacks. It requires you to deploy and configure a LEMP solution using a very popular Web Server – NGINX.

## 1. update ubuntu packages
sudo apt 

## 2. install nginx
sudo apt install nginx

sudo systemctl status nginx

sample output of installation result
![nginx server test](./images/install-nginx.png)

## 3. install mysql

sudo apt install mysql-server

sudo mysql

mysql describe database

exit

sample out put of default databases installed
![mysql installation](./images/mysql-installed.png)

## 4. install php and its dependencies

sudo apt install php-fpm php-mysql -y
![php installation](./images/php-installed.png)

## 5. defining domain root and ownership
![creating user and permission](./images/domain-root+ownership.png)

## 6. configure nginx

![configuring nginx](./images/configuring-nginx.png)

## 7. create user and grant priviledges 
![configuring nginx](./images/mysql-create-db_user.png)

## 8. create database and insert records

![configuring nginx](./images/mysql-db-operations.png)

## 9. create sample php-script 

![sample php script](./images/php-script.png)

![sample cript output](./images/php-script-output.png)