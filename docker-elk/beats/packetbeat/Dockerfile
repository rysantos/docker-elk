ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/beats/packetbeat:${ELK_VERSION}
EXPOSE 8080
# Auto-Create Kibana PacketBeat Dashboard Tables 
#RUN /usr/share/packetbeat/packebeat setup --dashboards
