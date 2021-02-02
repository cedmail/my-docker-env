FROM docker.elastic.co/elasticsearch/elasticsearch:7.10.2
LABEL maintainer="cmailleux@jahia.com"

RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install analysis-stempel && \
    /usr/share/elasticsearch/bin/elasticsearch-plugin install analysis-kuromoji
