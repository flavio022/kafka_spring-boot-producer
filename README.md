# kafka_spring-boot-producer

<h2>Start zookeeper server</h2>
zookeeper-server-start /usr/local/etc/kafka/zookeeper.properties

</br>

<h2>Start kafka server</h2>
kafka-server-start /usr/local/etc/kafka/server.properties
<h2>Creating a topic</h2>
 kafka-topics --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic kafka_example
