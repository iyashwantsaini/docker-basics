# install
* install docker and docker compose

# check version
* sudo docker version 

# check installation
* sudo docker run docker/whalesay cowsay hello_world!

# hello_world
* sudo docker run hello-world

# start docker
* sudo service docker start

# see all images
* sudo docker images

# run image
* sudo docker run -it <image_name>

# see running containers
* sudo docker ps -a

# execute conatiner
* sudo docker exec -t <container_id>

# stop container
* docker stop <container_id>

# create new image from alredy installed one
* docker commit <container_id> <repo_name>/<image_name>

# login
* docker login

# push to hub
* docker push <repo_name>/<image_nmae>

# delete image
* docker rmi <image_id>

# delete container
* docker rm <container_id>

# docker compose
* sudo docker-compose up

# docker compose view running
* docker-compose ps

# docker compose stopping containers
* docker-compose stop

# docker build 
* eg1 docker build -t flask-sample:latest .
* eg2 docker build -t flask-hello .

# docker run 
* docker run -d -p 5000:5000 flask-sample