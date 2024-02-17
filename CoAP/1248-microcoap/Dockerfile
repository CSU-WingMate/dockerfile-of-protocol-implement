FROM ubuntu:22.04
RUN apt-get update \
    && apt-get install -y sudo gcc make git \
    && cd /opt \
    && sudo git clone https://github.com/1248/microcoap.git \
    && cd microcoap \
    && make
