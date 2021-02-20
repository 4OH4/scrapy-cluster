ELK
===

This folder houses sample files used when integrating Scrapy Cluster with Elasticsearch, Logstash and Kibana. For more information please see Scrapy Cluster's official Documentation.

Last tested on Feb 20, 2021 with:

* Elasticsearch 7.10.2

* Filebeat 7.10.2

* Kibana 7.10.2

*Kibana configuration*: create an index pattern (Stack Management -> Index Patterns) using the pattern `filebeat-*`, and select `@timestamp` for the primary time field.