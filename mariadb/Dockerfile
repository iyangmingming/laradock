FROM mariadb:latest

LABEL maintainer="Mahmoud Zalt <mahmoud@zalt.me>"

RUN usermod -u 1000 mysql

ADD my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]

EXPOSE 3306
