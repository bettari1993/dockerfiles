FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/shar/local/nginx/html/index.html
COPY index.html /usr/shar/local/nginx/html/index.html
CMD [ "nginx", "-g", "deamon off;"  ]
LABEL Name="almalinux" \
      topic="dockerfile"


       