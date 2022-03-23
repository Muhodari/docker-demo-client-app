# A basic react application

## Getting started

- clone the repo
- cd `docker-compose-demo/client`


## Building image

This is to build an image for the client in case you want to learn the client in a separate container

### Building the image

```sh
 docker build . -t <docker-usernmae>/<appname>
 # docker build . -t patrickniyo/client
```

### Running the docker image

```sh
docker run -p <host-port>/<app exposed port> <image-name or image id>
# docker run -p 3000:3000 patrickniyo/client
```

### Publishing the image to docker hub

```sh
docker push <image name or image name
# docker push patrickniyo/client
```



