# What ?
Start dev env Symfony 4 on LAMP env.

# Technologies
* Docker Containerization
* Linux
* Apache
* MySQL
* PHP

# Framework
* Symfony 4

# How to ?
Build services : `docker-compose build`

Create/start containers : `docker-compose up -d`

bash access to sf4_php container : `docker exec -it -u dev sf4_php bash`


Compose project : `cd /home/wwwroot/sf4` & `composer create-project symfony/skeleton my-temp-folder`

```
cp -Rf /home/wwwroot/sf4/my-temp-folder/. .
rm -Rf /home/wwwroot/sf4/my-temp-folder
```

Go to `localhost` and enjoy :v: