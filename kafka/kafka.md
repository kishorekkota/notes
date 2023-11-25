### What is Kafka ?


Kafka is a Pub Sub Messaging middleware - oftentimes it is referred as Event Streaming platform. 

Difference ?

Messages are usually sent one - by - one, however Streaming works differently. Stream allows information to be batched and sent as packages than individual messages, this allows for high throughput with the ability to send multiple messages as once.

This capability need to be tuned carefully so it meet respective needs, this can be turned off as well by setting to Zero.

`buffer.memory=0` 

This will have evenr record send indivudually instead of batching.

What are the main components in a Kafka ?

Controller

Broker

Topic

Partitions

Connector

Producer

Consumer


What is Controk Plane ?

Control plane is the system which is responsible for managing, coordinating and controlling overall system behaior.

With in the context of Kafka, Kafka Controller is the Control Plane.


What is Data Plane ?

Data Plan is the system that is responsible for processing data. 

With in the context of Kafka, there are several components that makeup the Data Plane.

Broker, Producer, Consumer, Connector.

