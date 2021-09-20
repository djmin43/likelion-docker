FROM ubuntu:18.04

LABEL title="My Funny Valentine"

ARG MESSAGE="complete"

RUN adduser --disabled-password --gecos "" jaymin
RUN whoami

USER jaymin
RUN whoami

RUN echo $MESSAGE


