## About
Configuring a Linux server to host [Catalog project](https://github.com/FadyAlfred/RestaurantMenu)

## Server details
IP address: 35.189.9.180
SSH Port: 2200  
Username: grader  
URL site: <http://35.189.9.180/>  

## Software installed
1) Apache2
2) Postgresql
3) Sqlalchemy
4) Git
5) Flask
6) Oauth2client
7) Httplib2
8) Requests
9) Libapache2-mod-wsgi

## Changes made
1) Added grader user with sudo privilege
2) Added personal ssh key
3) Changed ssh port from 22 to 2200
4) Configured ufw to allow specified ports only(2200, 123, 80)
5) Created a new postgresql database called catalog with a user catalog
6) Setup .wsgi file and put it in the appliaction
7) Setup apache conf to serve flask application 
8) Run the app

## References used were
1) https://www.digitalocean.com/community/tutorials/how-to-setup-a-firewall-with-ufw-on-an-ubuntu-and-debian-cloud-server
2) https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
3) https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps
4) https://www.liquidweb.com/kb/changing-the-ssh-port/
5) https://discussions.udacity.com/c/nd004-p7-linux-based-server-configuration
