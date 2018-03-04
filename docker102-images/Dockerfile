FROM golang:latest

WORKDIR /go/src/github.com/dungeonmaster18/demo/

RUN go get -d -v github.com/gorilla/mux
COPY main.go .

RUN CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o app .

CMD ["./app"]