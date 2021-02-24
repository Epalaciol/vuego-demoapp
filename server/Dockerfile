FROM golang:1.16
WORKDIR /go/src
ENV PORT=4001
EXPOSE 4001
COPY . .
RUN go build
CMD ["./vuego-demoapp"]