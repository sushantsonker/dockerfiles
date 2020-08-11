FROM ubuntu
MAINTAINER Prashansa Kulshrestha
RUN apt-get update
RUN apt-get install -y python3.6
ADD hello.py /home/hello.py
ADD a.py /home/a.py
RUN apt-get install -y python3-pip
RUN pip3 install requests
CMD ["/home/hello.py"]
WORKDIR /home
ENTRYPOINT ["python3"]