# dandelion
git clone https://github.com/amashkin/dandelion.git

User: pi
Pwd: 123
192.168.88.20 (thrugh DHCP yet)

Raspberry Pi own project

1. Install latest OS
  ...
2. Install GPIO tool
  https://www.youtube.com/watch?v=G7vOe3zC9bw
3. Install python
  ...
4. Install Apache
  Apache web server: Build a local HTML server with a Raspberry Pi
  https://magpi.raspberrypi.com/articles/apache-web-server
5. Instal latest PHP
  sudo apt-get install php
  https://magpi.raspberrypi.com/articles/apache-web-server
6. Install MariaDB
  sudo apt install mariadb-server php-mysql -y
  sudo service apache2 restart
  //not perforemed: pi@raspberrypi:/var/www/html $ sudo mysql_secure_installation
  https://randomnerdtutorials.com/raspberry-pi-apache-mysql-php-lamp-server/

sudo apt-get update
sudo apt-get upgrade -y
sudo apt-get install apache2 -y
sudo apt-get install php
sudo apt install mariadb-server php-mysql -y
sudo chown -R pi /var/www/html
sudo service apache2 restart

9/05/2022
Plan
- start web server on Pi
- run PHP file
- run PHP file with command that starts pump 
