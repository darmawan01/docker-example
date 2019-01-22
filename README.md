# My Docker Command For Memories

```
    This repo for my note to remembering me to docker command
```

## Run first image

```
    -> docker container run --publish 80:80 nginx

    this docker run nginx image and publish to 80 port
```

```
    -> docker container run --publish 80:80 --detach nginx

    run nginx image to background
```

```
    -> docker container ls

    check running container adding '-a' it's mean showing all of container 
```

## Command

```
    -> docker container rm 'container id/name'

    adding -f to remove force cotnainer when container is runnning or used
```
```
    -> docker container stop 'container id/name'

    stoping docker container running
```