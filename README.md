docker build -t hello-rest-go .

docker run --rm -it -p 8080:8080 hello-rest-go
