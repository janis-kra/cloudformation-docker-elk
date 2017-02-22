FROM kibana:5.2

RUN apt-get update

ENV ELASTICSEARCH_ENDPOINT http://elasticsearch:9200

ENTRYPOINT ["/bin/bash", "-c", "kibana --elasticsearch $ELASTICSEARCH_ENDPOINT"]
