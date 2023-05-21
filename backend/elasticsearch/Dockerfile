FROM docker.elastic.co/elasticsearch/elasticsearch:8.7.1
RUN elasticsearch-plugin install analysis-nori && elasticsearch-plugin install analysis-icu

EXPOSE 9200
EXPOSE 9300
