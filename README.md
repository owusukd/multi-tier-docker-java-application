# Multi-tier Docker App
In this project, I deployed a java app which depends on MySQL database, RabbitMQ, Memcache, and Nginx for load balancing.
The docker image of the app, DB, and Nginx were built and uploaded onto Dockerhub, whiles memcache and rabbitmq were downloaded from Dockerhub.
The building and the deployment were done with a Docker compose file. 
