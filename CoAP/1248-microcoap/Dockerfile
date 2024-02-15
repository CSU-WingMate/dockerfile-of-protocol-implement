FROM ubuntu:22.04
RUN apt-get update \
    && apt-get sudo install -y gcc make \
    && cd /opt \
    && sudo git clone https://github.com/1248/microcoap.git \
    && cd microcoap \
    && make
