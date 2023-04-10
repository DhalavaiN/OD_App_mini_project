FROM ubuntu:latest

WORKDIR .

RUN apt update && apt install python3 python3-pip ffmpeg libsm6 libxext6 -y

COPY . .

RUN pip3 install flask flask flask_pymongo opencv-python

EXPOSE 8080

CMD ["python3","main.py"]
