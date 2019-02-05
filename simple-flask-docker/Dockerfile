FROM ubuntu:18.04

MAINTAINER Nobody Void "nobody.v.void@gmail.com"

RUN apt-get update -y
RUN apt-get install -y python3-pip

WORKDIR /app
COPY . /app
RUN pip3 install -r requirements.txt

ENTRYPOINT ["python3"]
CMD ["app.py"]
