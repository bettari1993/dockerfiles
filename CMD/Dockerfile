FROM almalinux:9

RUN dnf install -y epel-release && \
    dnf install -y nginx && \
    mkdir -p /run/nginx && \
    dnf clean all

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]