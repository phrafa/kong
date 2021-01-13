FROM node:12.17-alpine3.9

WORKDIR /usr/src/server

COPY . .

RUN apk update && \
    apk add git && \
    apk add curl

