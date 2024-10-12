ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM elastic/elasticsearch:${ELASTIC_VERSION:-8.15.2}

ENTRYPOINT ["/entrypoint.sh"]
