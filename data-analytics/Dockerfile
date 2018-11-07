FROM python:3.6.5-slim

RUN apt-get -y update
RUN apt-get -y install vim
RUN apt-get -y install git

COPY . /home
WORKDIR /home
RUN pip install -r requirements.txt