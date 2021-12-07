FROM golang:1.17.4-stretch

WORKDIR /app

ADD . /app/

RUN go mod tidy
RUN go mod verify

EXPOSE 8080

CMD ["go", "run", "main.go"]
