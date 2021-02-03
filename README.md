# Global Project Crowdfunding System with Elastic stack (ELK) on Docker

Based on the Docker images:

* Elasticsearch : docker.elastic.co/elasticsearch/elasticsearch:7.10.2
* Logstash(arm64 version) : docker.elastic.co/logstash/logstash:8.0.0-SNAPSHOT-arm64
* Logstash(basic version) : docker.elastic.co/logstash/logstash:7.10.2
* Kibana : docker.elastic.co/kibana/kibana:7.10.2
* MySql : mariadb:10.5.8-focal

By default, the stack exposes the following ports:

* 5001: Logstash TCP input
* 9200: Elasticsearch HTTP
* 9300: Elasticsearch TCP transport
* 5601: Kibana
* 3306: MySql
