FROM ubuntu:bionic
MAINTAINER Daljeet Singh (d.singh@cynux.com)

ENV DEBIAN_FRONTEND=noninteractive

ENV TZ=America/New_York

RUN apt-get update

RUN apt-get upgrade -y

RUN apt-get install -y apache2 php php-mysql php-gd php-mbstring php-intl


# Default command
CMD ["apachectl", "-DFOREGROUND"]