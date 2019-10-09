FROM solr:8
RUN /bin/solr-exporter -p 9854 -b http://localhost:8983/solr -f ./conf/solr-exporter-config.xml -n 8
EXPOSE 9854