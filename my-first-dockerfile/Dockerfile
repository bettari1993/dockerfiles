FROM ubuntu:letest
#set the working directory in the image
WORKDIR /app

#copy the files from host file system to image file system

COPY . /app

#install necessary packeges

RUN dnf update && dnf install -y python3 python3-pip

#run a command start the application
CMD [ "python3", "app.py" ]
