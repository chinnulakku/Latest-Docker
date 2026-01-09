FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://docs.docker.com/engine/install/centos /usr/share/nginx/html/index.html
CMD ["nginx", "-g","daemon off;"]