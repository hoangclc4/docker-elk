ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELASTIC_VERSION}

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
USER root

COPY ./postgresql/postgresql-42.4.0.jar /usr/share/logstash/logstash-core/lib/jars/postgresql-42.4.0.jar
