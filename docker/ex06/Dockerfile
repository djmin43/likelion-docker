FROM ubuntu:18.04

WORKDIR /html
ADD index.html .
RUN ["pwd"]
RUN ls -al

WORKDIR /inside-html
COPY index.html .
RUN ["pwd"]
RUN ls -al

