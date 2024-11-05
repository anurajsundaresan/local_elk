FROM docker.elastic.co/logstash/logstash:7.17.17
COPY pipeline.conf /usr/share/logstash/pipeline/pipeline.conf
COPY entrypoint.sh ./entrypoint.sh
CMD ./entrypoint.sh
