# quick-start

docker run -p 6080:80 -v /dev/shm:/dev/shm ophigeni/ubuntu:latest

# pull

docker pull ophigeni/ubuntu:latest

# clone-from-fcwu

git clone --recursive https://github.com/fcwu/docker-ubuntu-vnc-desktop

# Docker-build

docker build -t docker-ubuntu-ophigeni .

# Docker-Run

docker run -p 6080:80 docker-ubuntu-ophigeni
