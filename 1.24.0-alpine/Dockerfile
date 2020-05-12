FROM docker:latest
LABEL maintainer="mario@mvochoa.com"

ENV VERSION 1.24.0

RUN apk add --update --no-cache py-pip python-dev libffi-dev openssl-dev gcc libc-dev make gettext \
    && pip install docker-compose==${VERSION}