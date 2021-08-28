FROM golang:1.17-alpine3.14

WORKDIR /go/app

ARG CGO_ENABLED=0

RUN apk update \
    && apk add --no-cache git