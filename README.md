# Docker-hub-repo

#push image to docker hub

docker build . -t hello-docker-world

docker login

docker images
(take the id of the contsiner)

docker tag (container id) udvilk/create krpu docker hub repository name

docker push udvilk/create krpu docker hub repository name