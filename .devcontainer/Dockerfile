FROM python:latest

RUN apt-get update && \
      apt-get -y install sudo

RUN apt-get install --fix-missing -y xvfb

RUN pip install pandas matplotlib  jupyter imageio

# Set the working directory to /workspace
WORKDIR /workspace
