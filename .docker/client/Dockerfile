FROM node:12.17-alpine3.9

WORKDIR /usr/src/client

COPY . .

RUN apk update && \
    apk add git && \
    apk add curl

