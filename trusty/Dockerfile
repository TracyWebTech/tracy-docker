FROM ubuntu:trusty

MAINTAINER contato@tracy.com.br

ENV DEBIAN_FRONTEND=noninteractive

ADD sources.list /etc/apt/sources.list

RUN apt-get update
RUN apt-get install -y git python-dev python3-dev pypy-dev build-essential cmake python-pip libjpeg-dev zlib1g-dev libfreetype6-dev libmysqlclient-dev libpq-dev libev-dev gettext libxslt1-dev libxml2-dev mysql-server postgresql-9.3 libffi-dev libssl-dev

RUN pip install -U pip
RUN pip install virtualenv
RUN pip install tox
