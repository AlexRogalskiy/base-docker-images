FROM debian:8.5
MAINTAINER Dmitry Petrov <dmitry@fullstackml.com>

LABEL com.fullstackml = "true" \
      com.fullstackml.function = "base-docker-images/debian-aws-tool" \
      com.fullstackml.version = "1.0"

RUN apt-get update --fix-missing && \
    apt-get install -y python-pip && \
    pip install boto
