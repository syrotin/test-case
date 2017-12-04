FROM httpd:2.4

RUN apt update
RUN apt install libapache2-mod-wsgi-py3 -y

COPY public-html/ /usr/local/apache2/htdocs/
