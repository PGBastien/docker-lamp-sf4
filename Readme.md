# What ?
Start to develop Symfony 4 on LAMP env.

# Stack
* Docker Containerization
* Linux debian stretch
* Apache 2
* MySQL 5
* PHP 7.2.10-fpm
* Maildev

# Framework
* Symfony 4

# How to ?
Build services : `docker-compose build`

Create/start containers : `docker-compose up -d`

bash access to sf4_php container : `docker exec -it -u dev sf4_php bash`


Compose project : `cd /home/wwwroot/sf4` & `composer create-project symfony/skeleton project-name`

```
cp -Rf /home/wwwroot/sf4/project-name/. .
rm -Rf /home/wwwroot/sf4/project-name
```

Clean Sf cache for the `dev` environment : `bin/console ca:cl`

Go to `localhost` and enjoy :v: