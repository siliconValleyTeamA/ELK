# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:8.0.0-SNAPSHOT-arm64

USER root
COPY mysql-connector-java-5.1.49-bin.jar /opt/

# Add your logstash plugins setup here
RUN /bin/sh -c logstash-plugin install logstash-input-jdbc
RUN /bin/sh -c logstash-plugin install logstash-filter-aggregate
