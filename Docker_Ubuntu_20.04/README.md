# docker_ubuntu_template_20.04
New docker image for Ubuntu:20.04 - with python preinstalled

## Build with
docker build -t somename .

## Run with
docker run somename
or
docker run -d somename


#################

In addition to the above - below is how to work this with the concurrency-code examples.

Build with:
>docker build -t nomz/ubuntu_with_python3:0.0.2 .

Run Interactive shell with: 
>docker run --rm -it nomz/ubuntu_with_python3:0.0.2 /bin/bash
