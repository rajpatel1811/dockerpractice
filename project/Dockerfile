FROM ubuntu:latest
RUN apt-get update
RUN apt-get install vim -y
RUN apt-get install python3 -y

COPY src/server.py /tmp/

CMD ["python3", "/tmp/server.py"]
