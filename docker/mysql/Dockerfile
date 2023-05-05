FROM mysql:8.0.31-debian

ARG MYSQL_ROOT_PASSWORD
ARG MYSQL_DATABASE

ENV MYSQL_ROOT_PASSWORD ${MYSQL_ROOT_PASSWORD}
ENV MYSQL_DATABASE ${MYSQL_DATABASE}
ENV TZ Asia/Tokyo

RUN apt-get -y update && \
    apt-get -y install sudo vim

RUN touch /var/log/mysqld.log && \
    chmod 666 /var/log/mysqld.log

COPY my.cnf /etc/mysql
RUN chmod 644 /etc/mysql/my.cnf
