ARG ELK_VERSION

FROM docker.elastic.co/beats/filebeat:${ELASTIC_VERSION:-8.17.2}

COPY filebeat.yml /usr/share/filebeat/filebeat.yml
USER root

RUN mkdir /var/logs

RUN chown -R root /usr/share/filebeat