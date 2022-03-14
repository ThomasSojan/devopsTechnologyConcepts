# Kafka Concepts

## Publish/Subscribe messaging

* It's a messaging strategy where sender dosen't send data directly to reciever instead of that there is a **publisher** and **subcriber**
* Publisher classify messages without knowing if there is any subscriber interested in a particular type of message
* Reciever subscribes to recieve certain type of messages without knowing if there are senders sending those messages
* Pub/Sub system usually have **broker** where all messages are published.This decouples publishers from subscribers and also reduce no of potential connection between publishers and subscribers. Brokers classify messages in the form of certain **topics**

## Kafka
* Opensource pub/sub **messaging system**
* Also known as **distributed event log** where all the records are immutable and appended to the end of the log
* Messages are **persisted** on disk for certain period of time known as **retention-policy** makes kafka **hybrid** between messaging system and database
* 
* 

