Fake Edit
# Sourcefabric Airtime image for Docker

## Build locally
```
docker build -t docker-airtime .
```

## Run prebuilt image 
```
docker run -d -p 8080:80 -p 8000:8000 -t blane44/docker-airtime
``` 

Ports:
- Web: 8080
- Icecast2: 8000

Defaults:
- login: admin
- password: admin



## Docker Hub image
```
https://hub.docker.com/r/blane44/docker-airtime/
```

Forked from https://github.com/okvic77/docker-airtime
