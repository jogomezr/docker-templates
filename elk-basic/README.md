Source: https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-docker.html

Description: multi-node Elasticsearch and Kibana cluster setup.

How To:

Execute the following command to spin up the cluster: docker-compose up -d

Test it: curl -X GET "localhost:9200/_cat/nodes?v&pretty"

http://localhost:5601