FROM registry.access.redhat.com/ubi8/ubi

RUN yum -y update && yum -y install httpd && yum clean all

EXPOSE 80

CMD ["apachectl", "-D", "FOREGROUND"]