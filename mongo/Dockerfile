FROM mongo:latest

LABEL maintainer="Mahmoud Zalt <mahmoud@zalt.me>"

#COPY mongo.conf /usr/local/etc/mongo/mongo.conf

RUN usermod -u 1000 mongodb

VOLUME /data/db /data/configdb

CMD ["mongod"]

EXPOSE 27017

