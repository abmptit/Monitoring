#FROM elasticsearch
FROM docker.elastic.co/elasticsearch/elasticsearch:6.5.4
# --batch for non-interactive mode (auto-confirm warnings)
#RUN bin/elasticsearch-plugin install --batch x-pack
RUN bin/elasticsearch-plugin install --batch com.floragunn:search-guard-6:6.5.4-24.0
RUN echo "xpack.security.enabled: false" >> /usr/share/elasticsearch/config/elasticsearch.yml
RUN echo "http.cors.enabled: true" >> /usr/share/elasticsearch/config/elasticsearch.yml
RUN echo "http.cors.allow-origin: '*'" >> /usr/share/elasticsearch/config/elasticsearch.yml
