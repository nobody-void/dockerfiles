FROM ubuntu:18.04

MAINTAINER Nobody Void "nobody.v.void@gmail.com"

RUN apt-get update -y
RUN apt-get install -y net-tools iputil-* iproute2 tcpdump

ENV PATH="/app:$PATH"
WORKDIR /app
COPY . /app

ENTRYPOINT ["pause"]
