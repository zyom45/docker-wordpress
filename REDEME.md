## 1. install docker
install docker desktop and sign up your account
https://www.docker.com/

## 2. setting

###　Rename file to project name
Change the "PRJ-NAME" directory name to something arbitrary

###　Rename containers to project name
open docker-compose.yml,
Rename containers to project name.
ex. 
"prj_wordpress" >  "mysite_wordpress"
"prj_wordpress_db" >  "mysite_wordpress_db"
"prj_phpmyadmin" >  "mysite_phpmyadmin"

### .env setting

```
cp .env.example .env
```

## 3. Activate docker-compose
move sample file dir and do this command

```
docker-compose up -d
```

## 4. Start development
You can check WordPress by accessing the following URL
http://localhost:8080

### you can edit wp-content dir
The wp-content directory is created.
You can edit the wp-content directory.

### you can edit db
You can check phpMyAdmin by accessing the following URL
http://localhost:8081


**Now it's all done!** :tada::tada::tada: