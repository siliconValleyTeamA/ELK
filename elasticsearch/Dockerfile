# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:7.10.2

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
USER root
RUN usermod -u 1100 elasticsearch
USER elasticsearch

# 한국어 형태소 분석기 nori
RUN elasticsearch-plugin install analysis-nori
