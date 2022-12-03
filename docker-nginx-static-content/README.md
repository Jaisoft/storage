docker build . -t nginx-web

docker run -d -p 80:80 nginx-web

localhost:80
