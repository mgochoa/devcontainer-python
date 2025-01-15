FROM mcr.microsoft.com/devcontainers/python:1-3.12

RUN apt-get update && apt-get -y install --no-install-recommends awscli
ENV TZ=Europe/Amsterdam
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone