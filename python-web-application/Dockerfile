FROM ubuntu:latest

WORKDIR /app

COPY requirement.txt /app/

RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    pip install -r requirement.txt && \
    cd devops

ENTRYPOINT [ "python3" ]

CMD [ "manage.py", "runserver", "0.0.0.0:8000" ]


