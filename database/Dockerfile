FROM java:8

MAINTAINER Keiichiro Ono <kono@ucsd.edu>

RUN apt-get update && apt-get install -y build-essential wget

RUN mkdir /app
WORKDIR /app

RUN wget http://tinkerpop.com/downloads/rexster/rexster-server-2.4.0.zip
RUN unzip rexster-server-2.4.0.zip

RUN ls

