FROM ubuntu:14.04.2

MAINTAINER Ondrej Klejch

RUN apt-get update
RUN apt-get install -y wget build-essential python python-dev python-distribute python-pip
RUN pip install --install-option="--zmq=bundled" pyzmq
RUN pip install protobuf nose gevent==1.0.2

ADD . /usr/lib/python2.7/dist-packages/
