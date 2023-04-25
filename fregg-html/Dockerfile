FROM redhat/ubi9
RUN yum install -y httpd
COPY . /var/www/html
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
