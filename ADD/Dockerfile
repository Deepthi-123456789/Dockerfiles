FROM almalinux:latest
RUN yum install nginx -y
COPY index.html /tmp
ADD  https://raw.githubusercontent.com/daws-76s/notes/master/session-01.txt /tmp
CMD ["nginx","-g","daemon off;"]