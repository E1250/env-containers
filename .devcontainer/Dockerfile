FROM pytorch/pytorch:latest

RUN apt-get -y update && \
    apt-get install -y python3-pip libsm6 libxext6 libxrender-dev bash git

COPY *requirements.txt /app/requirements.txt

WORKDIR /app

RUN pip install --upgrade pip