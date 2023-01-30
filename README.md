 ## docker-compose goal
 creating a complete environment for a Wordpress application with data persistence and security. 
 
 ## Description
 setting up three services: db, wordpress, and webserver, all with their respective images and configurations. It is also using volumes to store persistent data and a shared network called "app-network." Additionally, it is using certbot to obtain an SSL certificate for the website.

 ## Run it 
 docker-compose up -d
 
 note: add the .env file with the correspondent variables.
 