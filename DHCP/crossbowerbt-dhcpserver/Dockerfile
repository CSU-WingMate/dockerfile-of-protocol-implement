FROM ubuntu:22.04
RUN apt-get update \
  	&& apt-get install sudo \
    && sudo apt-get install git make gcc net-tools -y \
    && cd /opt \
    && sudo git clone https://github.com/crossbowerbt/dhcpserver.git \
    && cd ./dhcpserver \
    && make
