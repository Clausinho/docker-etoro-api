
Unofficial API for eToro, wrapping https://github.com/ok24601/etoro-api into a docker image.

## RUN

### docker run

1. docker run --shm-size=1g -p 8088:8088 -e LOGIN=user -e PASSWORD=ooooooooo -it --rm --name my-etoro-api etoroapi

or 

### docker compose

1. edit .env-example with user and password for etoro and rename it to ".env"
2. docker-compose up