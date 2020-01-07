# base image: old release
FROM ubuntu:16.04
# name of the maintainer of this image
MAINTAINER Sandeep Dhara
# install the latest upgrades
RUN apt-get update && apt-get -y dist-upgrade
# install the package
RUN apt-get -y install apache2 
# set the default container command
CMD [ "/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
