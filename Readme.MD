##

docker file is a declarative way of creating our own images.docker will givve somesyntax to create our own images

file name should me Dockerfile

##
## how to build images from Dockerfile 

docker build -t [docker-hub-url]/[your-username]/[image-name]:version .

### how to push images to dockerhub

docker push [docker-hub-url]/[your-username]/[image-name]:version