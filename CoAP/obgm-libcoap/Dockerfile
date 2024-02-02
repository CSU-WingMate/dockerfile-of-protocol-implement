FROM ubuntu:22.04
RUN apt-get update \
    && apt-get install sudo \
    && sudo apt-get install git -y \
    && cd /opt \
    && sudo git clone https://github.com/obgm/libcoap.git \
    && cd ./libcoap \
    && sudo apt-get install -y autoconf automake pkgconf libtool doxygen asciidoc \
    && ./autogen.sh \
    && ./configure --disable-dtls \
    && make \
    && make install
