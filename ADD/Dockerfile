FROM almalinux:latest
RUN yum install nginx -y
COPY index.html /tmp
ADD  https://github.com/Deepthi-123456789/terraform-aws-security-group/blob/main/main.tf /tmp
CMD ["nginx","-g","daemon off;"]