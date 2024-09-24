FROM almalinux:latest
RUN yum install nginx -y
COPY index.html /tmp
ADD  https://raw.githubusercontent.com/Deepthi-123456789/multiple-env/refs/heads/main/tfvars/roboshop.tf /tmp
CMD ["nginx","-g","daemon off;"]