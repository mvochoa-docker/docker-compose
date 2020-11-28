FROM docker:stable

ENV VERSION 1.27.4

RUN apk add --update --no-cache py-pip python3-dev libffi-dev openssl-dev gcc libc-dev make gettext curl git \
    && pip install docker-compose==${VERSION}