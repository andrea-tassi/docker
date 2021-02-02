# Docker

## Set up Ubuntu workspace

1. Login with your Docker ID to push and pull images from Docker Hub.

    My DockerHub: [dretaxi/ubuntu_dev](https://hub.docker.com/r/dretaxi/ubuntu_dev)

       docker login

2. Pull the latest image:

       docker pull dretaxi/ubuntu_dev:latest
      
3. Build it:

       docker build -f Dockerfile -t dretaxi/ubuntu_dev .
      
4. Run it:
      
       docker container run -it -v ~/dev:/root/dev dretaxi/ubuntu_dev /bin/zsh
       
5. Modify it and then push:

       docker push dretaxi/ubuntu_dev



      
