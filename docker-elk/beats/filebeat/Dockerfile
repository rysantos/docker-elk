ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/beats/filebeat:${ELK_VERSION}

COPY config/filebeat.yml /usr/share/filebeat/filebeat.yml
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
RUN chmod 644 /usr/share/filebeat/filebeat.yml
USER filebeat