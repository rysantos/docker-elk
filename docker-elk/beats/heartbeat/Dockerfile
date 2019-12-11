ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/beats/heartbeat:${ELK_VERSION}

# Auto-Create Kibana Heartbeat Dashboard Tables 
#RUN /usr/share/heartbeat/heartbeat setup --dashboards