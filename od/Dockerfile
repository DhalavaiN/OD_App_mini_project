FROM ubuntu:latest

WORKDIR .

RUN apt update && apt install python3 python3-pip -y

COPY . .

RUN pip3 install flask flask flask_pymongo opencv-python

EXPOSE 5000

CMD ["python3","main.py"]
