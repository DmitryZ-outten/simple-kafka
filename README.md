External CLI client

/kafka/bin/kafka-topics.sh --zookeeper localhost:2181 --create --topic kafka-test-topic --replication-factor 1 --partitions 2

/kafka/bin/kafka-topics.sh --zookeeper localhost:2181 --describe --topic kafka-test-topic

/kafka/bin/kafka-console-producer.sh --broker-list localhost:9092 --topic kafka-test-topic

/kafka/bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic kafka-test-topic
