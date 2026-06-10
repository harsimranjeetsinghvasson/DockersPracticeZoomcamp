# DockersPracticeZoomcamp    1  python - V
    2  docker
    3  PS1="> "
    4  docker run hello-world
    5  docker run -it ubuntu
    6  clear
    7  python -V
    8  exit()
    9  PS1="> "
   10  pwd
   11  ls
   12  docker run -it --entrypoint=bash -V $(pwd) python:3.13.11-slim
   13  docker run -it --entrypoint=bash -v $(pwd) python:3.13.11-slim
   14  docker ps -a
   15  docker -rm `docker ps -aq`
   16  docker rm `docker ps -aq`
   17  docker ps -a
   18  docker run -it --entrypoint=bash -V $(pwd)/test:/app/test  python:3.13.11-slim
   19  docker run -it --entrypoint=bash -v $(pwd)/test:/app/test  python:3.13.11-slim
   20  ls
   21  history >> README.md
