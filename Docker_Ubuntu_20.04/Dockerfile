FROM ubuntu:latest

#RUN apt-get update
RUN apt update
RUN apt upgrade -y
RUN apt install vim -y
#RUN apt-get install python3-pip -y
RUN apt install python3-pip -y
#RUN apt-get install python3.8 -y
RUN apt install python3.8 -y
RUN apt install python3-dev libpq-dev -y
WORKDIR /
CMD ["mkdir", "/code"]

COPY code /code

#CMD ["python3", "/code/main.py"]
