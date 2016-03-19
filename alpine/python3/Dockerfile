From alpine
MAINTAINER Stan Liu

RUN apk update
RUN apk add bash ffmpeg exiftool python3 curl
RUN ["curl", "-O", "https://bootstrap.pypa.io/get-pip.py"] 
RUN ["/usr/bin/python3", "get-pip.py"]
RUN pip install requests hug click path.py pytest nose pudb 
