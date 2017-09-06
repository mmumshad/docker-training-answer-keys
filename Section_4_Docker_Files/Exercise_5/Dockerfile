# Our source code is located at /home/dev_user/source-code/app.py. Copy it over to the location /opt/app.py inside the Docker container

FROM ubuntu:17.04

RUN apt-get update

RUN apt-get install -y python python-pip

RUN pip install flask

COPY /home/dev_user/source-code/app.py /opt/app.py

