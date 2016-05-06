FROM ubuntu:14.04
MAINTAINER Thinh "Adolf Weismann" Tran <duythinht@gmail.com>
RUN apt-get update && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
RUN apt-get install -y nodejs
ENTRYPOINT ["node"]
