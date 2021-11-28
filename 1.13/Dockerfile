FROM golang:1.17.3-bullseye 
WORKDIR /usr/src/app
COPY . .
EXPOSE 8080
RUN go build
CMD ./server
