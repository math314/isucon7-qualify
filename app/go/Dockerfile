FROM golang:1.10

COPY . /home/isucon/isubata/webapp/go
WORKDIR /home/isucon/isubata/webapp/go
RUN make

EXPOSE 5000

ENTRYPOINT ["/home/isucon/isubata/webapp/go/isubata"]
