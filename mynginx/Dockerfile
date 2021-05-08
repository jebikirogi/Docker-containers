FROM ubuntu
MAINTAINER NAME (jebikirogi@gmail.com)
RUN apt-get update
RUN apt-get install nginx -y
EXPOSE 80 443
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
