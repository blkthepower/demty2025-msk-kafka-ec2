# demty2025-msk-kafka-ec2

These files show the way to consume an AWS MSK serverless Kafka cluster.


**Cluster**
The example cluster has IAM authentication enabled and is referenced as the `broker`.

**Producer**

Sends messages to a target topic.

**Consumer**

Reads the messages from the topic

**Topic**

Helps to organize messages in Kafka.


## HOW TO

**Install the required libraries**
```
pip install kafka-python
pip install aws-msk-iam-sasl-signer-python
```

**Execute the topic**
```
python topic.py
```

**Execute the producer**
```
python producer.py
```

**Execute the consumer**
```
python consumer.py
```

**Optionally, execute delete to remove the topic**
```
python delete.py
```