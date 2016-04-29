# docker-ethereum

This is the repository for the kunstmaan/ethereum-{g}eth docker images.

## Images

* [kunstmaan/ethereum-eth](https://hub.docker.com/r/kunstmaan/ethereum-eth/): An Ubuntu 16.04 image with the Ethereum C++ eth binaries installed.
* [kunstmaan/ethereum-geth](https://hub.docker.com/r/kunstmaan/ethereum-geth/): An Ubuntu 16.04 image with the Ethereum Go geth binaries installed.
* [kunstmaan/ethereum-geth-devnet](https://hub.docker.com/r/kunstmaan/ethereum-geth-devnet/): The geth image running a devnet
* [kunstmaan/ethereum-geth-testnet](https://hub.docker.com/r/kunstmaan/ethereum-geth-testnet/): The geth image running a testnet
* [kunstmaan/ethereum-geth-console](https://hub.docker.com/r/kunstmaan/ethereum-geth-console/): The geth image with two helper commands to connect to the test or devnet


## Running

Use this [docker-compose.yml](https://github.com/Kunstmaan/docker-ethereum/blob/master/docker-compose.yml) and run:

```
docker-compose up -d
```

## Connecting to an image

Run `docker ps`to find the name of the container and attach to it by running `docker attach <containername>`
