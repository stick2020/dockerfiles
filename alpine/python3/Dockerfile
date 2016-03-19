From alpine
MAINTAINER Stan Liu

RUN apk update
RUN apk add bash ffmpeg exiftool python3 curl
RUN ["curl", "-O", "https://bootstrap.pypa.io/get-pip.py"] 
RUN ["/usr/bin/python3", "get-pip.py"]
RUN apk add python3-dev libjpeg tiff-dev freetype-dev lcms2-dev tcl-dev gcc musl-dev
RUN ["ln", "-s", "/lib/libz.so", "/usr/lib"]
RUN pip install click hug mock nose path.py pep8 pillow pudb pyflakes pytest requests
