FROM golang:1.16

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

ENV REQUEST_ORIGIN="http://example.com"

RUN go build

CMD [ "./server" ]