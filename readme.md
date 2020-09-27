# Docker-compose Symfony
This repository is a docker-compose template to build symfony project, it use Nginx, php7.4, nodeJs, yarn, mysql, phpmyadmin, maildev.
**Don't forget to create a mysql folder to match with configuration.**	

# Clone
Go to project folder and use terminal **git clone https://github.com/sitrak123/phpSfDocker.git**  
Go to folder after clone, and use **sudo docker-compose up --build** to build docker image.    
Wait and when build is done, go to browser and go to localhost:8080 to see symfony welcome page.    

To install symfony latest project:  
* symfony new  --full symfony --dir=/var/www/symfony  

_Inspired by meduim article_