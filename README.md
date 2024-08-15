# Donwload and the set up of the application

1. Ensure that the routes following in the docker-compose.yml are correct in your local machine, you need to check the following lines.

 - [First declaration of the volume php- fpm file ](https://github.com/nkymf/lleego-docker/blob/main/docker-compose.yml#L15).
- [Second declaration of the volume in nginx file](https://github.com/nkymf/lleego-docker/blob/main/docker-compose.yml#L32).


2. Boot up the docker with
```
    docker compose up -d --build
```

3. Enter the container, since you will use all of it for the following commands and development.
```
    docker exec -it development-back /bin/bash
```