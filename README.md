# Kafka-Commands

Most Commonly Used Kafka Commands

1. Kafka-topcis —zookeeper 127.0.0.1:2181 —topic topicName —create —partitions 3 —replication-factor 3

2. Kafka-topcis —zookeeper 127.0.0.1:2181 —list

3. Kafka-topcis —zookeeper 127.0.0.1:2181 —topic topicName describe

4. Kafka-topcis —zookeeper 127.0.0.1:2181 —topic topicName —delete

5. Kafka-producer-console —broker-list 127.0.0.1:2181 —topic topicName

6. Kafka-producer-console —broker-list 127.0.0.1:2181 —topic topicName —producer-property asks=all

7. Kafka-producer-console —broker-list 127.0.0.1:2181 —topic topicName

8. Kafka-consumer-console —bootstrap-server 27.0.0.1:2181 —topic topicName

9. Kafka-consumer-console —bootstrap-server 27.0.0.1:2181 —topic topicName —from-beginning

10. Kafka-consumer-console —bootstrap-server 27.0.0.1:2181 —topic topicName —group groupName

11. Kafka-consumer-console —bootstrap-server 27.0.0.1:2181 —topic topicName —group groupName —from-beginning

12. Kafka-consumer-groups —bootstrap-server localhost:9092 —list

13. Kafka-consumer-groups —bootstrap-server localhost:9092 —describe —group groupName

14. Kafka-consumer-groups —bootstrap-server localhost:9092 —describe —group groupName —reset-offsets —to-earliest —execute —topic topicName

15. Kafka-consumer-groups —bootstrap-server localhost:9092 —describe —group groupName —reset-offsets —shift-by -2 —execute —topic topicName
