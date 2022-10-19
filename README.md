# wordpress-nginx-php-mysql
Wordpress Deployment using nginx, PHP, MYSQL 


Installing Wordpresss using Nginx, MySQL,PHP setup

Step 1 : Installing Docker and Docker-Compose
•	Launch an ec2  instance for ubuntu and Log into it using ssh and .pem

•	Install Docker into it
$ sudo  apt-get update
$ sudo apt-get upgrade
$ sudo apt-get -y install docker.io
$ sudo systemctl  start docker
$ sudo  systemctl enable docker
$ sudo docker -v

•	Install Docker-compose in it
$ sudo apt-get update
$ sudo apt-get install -y python python3-pip
$ pip install docker-compose
$ docker-compose -v

Step 2 : Creating nginx ,PHP, MySQL images
•	$ sudo su –
•	$ mkdir wordpress
•	$ cd wordpress
•	$ touch docker-compose.yml
•	$ mkdir nginx
•	$ nano nginx/wordpress.conf
•	$ nano docker-compose.yml

 
Source : https://github.com/akshaykumart/wordpress-nginx-php-mysql.git

Step 3 :Verification:
Go to browser:    <ip address of the instance>

