FROM centos

LABEL version=1.0
LABEL description="esto es un test"

RUN yum install httpd -y

WORKDIR /var/www/html

COPY startbootstrap .

ENV contenido prueba

RUN echo "$contenido" > /var/www/html/prueba.html

COPY run.sh /run.sh

CMD sh /run.sh


