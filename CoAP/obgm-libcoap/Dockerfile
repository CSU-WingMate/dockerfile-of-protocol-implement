FROM ubuntu:22.04
RUN apt-get update \
    && apt-get install sudo git autoconf automake pkgconf libtool doxygen asciidoc -y \
    && cd /opt \
    && sudo git clone https://github.com/obgm/libcoap.git \
    && cd ./libcoap \
    && ./autogen.sh \
    && ./configure --disable-dtls \
    && make \
    && make install
