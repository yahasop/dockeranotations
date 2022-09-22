# dockeranotations
This is only my docker anotations while i'm learning it


docker pull: to pull an image from docker hub. We can perform run also but it will do the same as pull if the image it's not locally.
  docker pull ubuntu:latest

docker run to run a command into a new container. It will pull from docker hub if is not locally stored.
  docker run hello world

docker ps: to list all running containers

docker exec: to run a command in a running container
  docker exec -it ubuntu bash (flags i and t to make and interactive command entry and bash for that it's the command line ubuntu uses, but i think it can also be sh)
  
