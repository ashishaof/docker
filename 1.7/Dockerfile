FROM ubuntu:18.04

RUN apt-get update
RUN apt-get install -y curl
RUN apt-get install -y bash

ADD curler.sh /

RUN chmod +x /curler.sh

CMD /curler.sh
