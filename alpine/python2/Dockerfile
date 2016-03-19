From alpine
MAINTAINER Stan Liu

RUN apk update
#RUN apk add ffmpeg exiftool python bash py-pip 
RUN apk add bash ffmpeg exiftool python curl
RUN ["curl", "-O", "https://bootstrap.pypa.io/get-pip.py"] 
RUN ["/usr/bin/python", "get-pip.py"]
RUN pip install requests hug click path.py pytest nose pudb 
