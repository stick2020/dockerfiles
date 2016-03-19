From alpine
MAINTAINER Stan Liu

RUN apk update
#RUN apk add ffmpeg exiftool python bash py-pip 
RUN apk add bash ffmpeg exiftool python curl
RUN ["curl", "-O", "https://bootstrap.pypa.io/get-pip.py"] 
RUN ["/usr/bin/python", "get-pip.py"]
RUN apk add python-dev libjpeg tiff-dev freetype-dev lcms2-dev tcl-dev gcc musl-dev
RUN ["ln", "-s", "/lib/libz.so", "/usr/lib"]
RUN pip install click mock nose path.py pep8 pillow pudb pyflakes pytest requests
