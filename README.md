# docker-ethereum

This is the repository for the kunstmaan/ethereum-{g}eth docker images.

## Images

* [kunstmaan/ethereum-eth](https://hub.docker.com/r/kunstmaan/ethereum-eth/): An Ubuntu 15.10 image with the Ethereum C++ eth binaries installed.
* [kunstmaan/ethereum-geth](https://hub.docker.com/r/kunstmaan/ethereum-geth/): An Ubuntu 15.10 image with the Ethereum Go geth binaries installed.

## Running

Use this [docker-compose.yml](https://github.com/Kunstmaan/docker-ethereum/blob/master/docker-compose.yml) and run:

```
docker-compose up -d
```

## Connecting to an image

Run `docker ps`to find the name of the container and attach to it by running `docker attach <containername>`
