# Kafka Concepts

## Publish/Subscribe messaging

* It's a messaging strategy where sender dosen't send data directly to reciever instead of that there is a **publisher** and **subcriber**
* Publisher classify messages without knowing if there is any subscriber interested in a particular type of message
* Reciever subscribes to recieve certain type of messages without knowing if there are senders sending those messages
* Pub/Sub system usually have **broker** where all messages are published.This decouples publishers from subscribers and also reduce no of potential connection between publishers and subscribers. Brokers classify messages in the form of certain **topics**

## Kafka
* Opensource pub/sub **messaging system**
* Also known as **distributed event log** where all the records are immutable and appended to the end of the log
* Messages are **persisted** on disk for certain period of time known as **retention-policy**. This makes kafka **hybrid** between messaging system and database
* The main concept behand kafka are **producers**(publishers) producing messages to specific **topics** and **consumers**(recievers) consuming those messages and maintaining the position in the stream of data

## Kafka Architecture
* Architecture consist of **cluster**, **producers** and **consumers**
* Single kafka server within the cluster are brokers. The **broker** is responsible for reciving messages from producers, assigining offsets and commiting messages to disk
* Also responsible for responding to consumers fetch requests and serving messages
* When messages are send to a particular broker they are send to a particular topic. **Topics** provide a way to categorize data that is been send and they can be further broken down into number of **partitions**
* For example a system can have seperate topics for processing user and processing metric. Each partitions acts as a separate commit log and order of messages guaranteed only across the same partition
* Being able to split a topic to multiple partition makes scaling easy as each partition can be read by a separate consumers this allows for achieving high throughput as both partitions and consumers can be split across multiple servers

