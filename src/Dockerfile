FROM golang:1.8

WORKDIR /go/src/app

COPY ./cmd /go/src/app

RUN go get -d -v ./...
RUN go install -v ./...

EXPOSE 80

CMD ["app"]

