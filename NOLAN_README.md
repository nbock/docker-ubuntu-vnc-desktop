*ALIENS HAVE ARRIVED!*

Make sure to use `Dockerfile.arm64` if you are an alien!!!!!!!!!!!

Copy it into `Dockerfile`.

Once you pull, run:
1. git submodule update
2. git submodule init

Now you are ready to build your container:
1. docker build -t docker-vnc .
2. docker run -p 6080:80 -p 5900:5900 -v /dev/shm:/dev/shm docker-vnc

Now you can go to `http://127.0.0.1:6080/` and see your wonderful Ubuntu instance.

Ping me with questions.