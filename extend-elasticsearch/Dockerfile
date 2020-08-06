FROM docker.elastic.co/elasticsearch/elasticsearch:7.8.0
LABEL maintainer="cmailleux@jahia.com"

RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install analysis-stempel && \
    /usr/share/elasticsearch/bin/elasticsearch-plugin install analysis-kuromoji
