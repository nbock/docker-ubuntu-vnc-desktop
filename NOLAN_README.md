git submodule update

git submodule init

docker build -t docker-vnc .

docker run -p 6080:80 -p 5900:5900 -v /dev/shm:/dev/shm docker-vnc