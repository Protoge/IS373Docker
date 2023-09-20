# IS373Docker

## Docker Commands

- docker ps - lists running containers
- docker stop - stops running container (not delete)
- docker kill - faster than stop (leaves trash in the system) _DON'T RECOMMEND_
- docker pull
- docker images
- docker image rm <image id>
- docker run -it <image name> - runs image in interactive terminal mode
- docker stats
- options:
  --name
  -dp <external port: internal port> (8080:80)
  - Examples:
    docker run -dp 8080:80
    docker run --name apache-23 -dp 8080:80
    dokcer run -it ubuntu
- docker rm <containername>
