# Kafka Concepts

## Publish/Subscribe messaging

* It's a messaging strategy where sender dosen't send data directly to reciever instead of that there is a **publisher** and **subcriber**
* Publisher classify messages without knowing if there is any subscriber interested in a particular type of message
* Reciever subscribes to recieve certain type of messages without knowing if there are senders sending those messages
* Pub/Sub system usually have **broker** where all messages are published. This decouples publishers from subscribers and also reduce no of potential connection between publishers and subscribers

