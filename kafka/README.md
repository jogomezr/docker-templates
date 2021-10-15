Source: https://www.baeldung.com/ops/kafka-docker-setup

Description: multi-node Kafka cluster setup. A cluster setup for Apache Kafka needs to have redundancy for both Zookeeper servers and the Kafka servers.

How To:

Execute the following command to spin up the cluster: docker-compose up -d

Test it using Offset Explorer and the Advanced tab to provide the list of available hosts.