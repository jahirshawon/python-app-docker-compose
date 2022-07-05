##here we build a pyrhon app image and run in container 
##this is simple app to count web hits
##in docker compose file here in web section we use build context which will build a image from dockerfile
#commands


docker-compose up -d ##this command build a new image and run container
docker-compose up -d --build ##if we change in source code we can rebuild from run time woithout down old container
docker ps #check running container

##from web browser 192.168.0.10:5000 , we ca check the app
 
