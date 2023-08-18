FROM golang:alpine

WORKDIR /app
RUN apk update &\
  apk add git
RUN go install github.com/cosmtrek/air@latest

