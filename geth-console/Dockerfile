FROM kunstmaan/ethereum-geth
MAINTAINER Roderik van der Veer

ADD ./geth-attach-devnet.sh /root/geth-attach-devnet.sh
RUN chmod +x /root/geth-attach-devnet.sh

ADD ./geth-attach-testnet.sh /root/geth-attach-testnet.sh
RUN chmod +x /root/geth-attach-testnet.sh
