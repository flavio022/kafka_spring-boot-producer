# kafka_spring-boot-producer

#Start zookeeper server
zookeeper-server-start /usr/local/etc/kafka/zookeeper.properties

</br>

#Start kafka server
kafka-server-start /usr/local/etc/kafka/server.properties
#Creating a topic
 kafka-topics --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic kafka_example
