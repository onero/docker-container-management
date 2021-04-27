# docker-container-management
Container management for Docker

## This project serves a docker container management environment, based on [Watchtower](https://github.com/containrrr/watchtower) and [Portainer](https://github.com/portainer/portainer)

## Requirements
In order to utilize this image, you only need to have the latest version of docker installed!

## Usage

1. Download the docker-compose file to the root of your Ionic project.
2. Run the following command

```
docker compose-up
```

This way you will see the output of the container.
The app will be served at
[localhost:9000 ](http://localhost:9000)

If you want to run the container without seeing the output simply run:
```
docker-compose up -d
```

If you want to attach a shell execute the the following command:
```
docker exec -it {NameOfYouContainer} /bin/sh
```
E.g.
```
docker exec -it myAwesomeApp_ionic_1 /bin/sh
```