# Run following command on terminal

docker build --tag=101371241_hello_docker .

# another way

docker build -t 101371241_hello_docker .

docker image ls

docker run -d --name=lab11DevOps -p 4000:80 101371241_hello_docker

docker container stop CONTAINER_ID

docker container ls