FROM ubuntu:wily
MAINTAINER Roderik van der Veer

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && \
    apt-get upgrade -q -y && \
    apt-get dist-upgrade -q -y && \
    apt-get install -q -y software-properties-common && \
    add-apt-repository ppa:ethereum/ethereum && \
    apt-get update && \
    apt-get install -q -y eth solc && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

EXPOSE 8545
EXPOSE 30303
