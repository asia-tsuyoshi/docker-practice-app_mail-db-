FROM --platform=linux/amd64 mysql:5.7

COPY ./docker/db/my.cnf /etc/my.cnf
RUN mkdir /var/log/mysql && \
    touch /var/log/mysql/query.log /var/log/mysql/error.log && \
    chmod 777 /var/log/mysql/query.log /var/log/mysql/error.log

