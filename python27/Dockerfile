FROM ubuntu:14.04
MAINTAINER Thinh "Adolf Weismann" Tran <duythinht@gmail.com>
RUN apt-get update
RUN apt-get install -y python-dev curl
RUN curl https://bootstrap.pypa.io/get-pip.py | python
ENTRYPOINT ["python"]
