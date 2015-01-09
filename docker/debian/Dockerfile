
# Debian stable.
# version 0.0.1
# Start with ubuntu precise (LTS).
FROM debian:stable

MAINTAINER stansage <me@stansage.com>

# Never ask for confirmations
ENV DEBIAN_FRONTEND noninteractive
#RUN echo "debconf shared/accepted-oracle-license-v1-1 select true" | debconf-set-selections
#RUN echo "debconf shared/accepted-oracle-license-v1-1 seen true" | debconf-set-selections
# Update apt
RUN apt-get update
# First, install add-apt-repository and bzip2
RUN apt-get -y install openssh-server
