FROM golang 
WORKDIR /work
RUN apt-get update 
RUN apt-get clean
RUN apt-get install golang-go iproute2 -y
ADD main.go .
CMD ["go", "run", "main.go"]
