# Kafka-Commands

Most Commonly Used Kafka Commands

1. zookeeper-server-start.sh config/zookeeper.properties

2. kafka-topics.sh --zookeeper 127.0.0.1:2181 --topic topicName --create --partitions 3 --replication-factor 3

3. kafka-topics.sh --zookeeper 127.0.0.1:2181 --list

4. kafka-topics.sh --zookeeper 127.0.0.1:2181 --topic topicName --describe

5. kafka-topics.sh --zookeeper 127.0.0.1:2181 --topic test-tpic --delete

6. kafka-console-producer.sh --broker-list 127.0.0.1:9092 --topic topicName

7. kafka-console-producer.sh --broker-list 127.0.0.1:9092 --topic kafka-events-util --producer-property asks=all

8. kafka-console-consumer.sh --bootstrap-server 127.0.0.1:9092 --topic topicName

9. kafka-console-consumer.sh --bootstrap-server 127.0.0.1:9092 --topic topicName --from-beginning

10. kafka-console-consumer.sh --bootstrap-server 127.0.0.1:9092 --topic topicName --group groupName

11. kafka-console-consumer.sh --bootstrap-server 127.0.0.1:9092 --topic topicName --group groupName --from-beginning

12. kafka-consumer-groups.sh --bootstrap-server localhost:9092  --list

13. kafka-consumer-groups.sh --bootstrap-server localhost:9092 --describe --group groupName

14. Kafka-consumer-groups —bootstrap-server localhost:9092 —describe —group groupName —reset-offsets —to-earliest —execute —topic topicName

15. Kafka-consumer-groups —bootstrap-server localhost:9092 —describe —group groupName —reset-offsets —shift-by -2 —execute —topic topicName

16. kafka-server-start.sh config/server.properties
