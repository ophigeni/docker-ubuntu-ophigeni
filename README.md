# ubuntu 22.04
docker run --rm -p 6080:80 -e RESOLUTION=1530x740 ophigeni/ubuntu-dball:latest

# ubuntu 20.04
docker run --rm -p 6080:80 -e RESOLUTION=1530x740 ophigeni/ubuntu-onepiece:latest   

docker run -p 6080:80 -v /dev/shm:/dev/shm ophigeni/ubuntu-anime:latest

docker run -p 6080:80 -v /dev/shm:/dev/shm ophigeni/ubuntu:latest

# pull

docker pull ophigeni/ubuntu-anime:latest

docker pull ophigeni/ubuntu:latest

# clone-from-fcwu

git clone --recursive https://github.com/fcwu/docker-ubuntu-vnc-desktop

# Docker-build

docker build -t docker-ubuntu-ophigeni .

# Docker-Run

docker run -p 6080:80 docker-ubuntu-ophigeni
