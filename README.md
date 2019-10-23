# Commands to Run in Terminal
1. docker build -t webserver-image:v1 .
2. docker run -d -p 80:80 webserver-image:v1

# to see running project 
got to => http://localhost/

# example docker commands
1. docker ps -a (see all the docker containers  running and stopped)
2. docker kill <container id> (to kill running docker container)
3. docker images -a (See all the docker images)
4. docker rmi <imageid> (remove docker images from machine)
