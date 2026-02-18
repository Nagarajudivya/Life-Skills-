# Messaging Queues & Enterprise Message Bus

---

## What are Messaging Queues?

- A Messaging Queue is a communication mechanism used to send messages between applications or services asynchronously.
- Messages are stored in a queue until the receiving system is ready to process them.
- A producer sends messages to the queue, and a consumer reads and processes them.
- The sender and receiver do not need to be active at the same time.

---

## Why Messaging Queues are Used?

- **Asynchronous Communication** — Sender does not wait for the receiver to respond.
- **Loose Coupling** — Services are independent and can change without breaking others.
- **Improved Scalability** — Multiple consumers can process messages in parallel.
- **Reliability** — Messages are not lost if a service temporarily fails.
- **Load Balancing** — Workload is distributed across multiple consumers.
- **Fault Tolerance** — If one consumer fails, another can take over.

---

## How Messaging Queues Work?

1. Producer sends a message to the queue.
2. Queue stores the message safely.
3. Consumer retrieves and processes the message.
4. Message is deleted after successful processing.

---

## Popular Messaging Queue Tools

| Tool | Description |
|------|-------------|
| **RabbitMQ** | Open-source message broker. Uses AMQP protocol. Common in microservices. |
| **Apache Kafka** | Distributed event streaming platform. High throughput and scalability. Used for real-time data pipelines. |
| **ActiveMQ** | Java-based message broker. Supports multiple protocols. |
| **Amazon SQS** | Fully managed message queue service (AWS). |
| **Azure Service Bus** | Cloud-based messaging service (Microsoft). |

---

## What is Enterprise Message Bus?

- An **Enterprise Message Bus (EMB)** or **Enterprise Service Bus (ESB)** is a central communication backbone used to integrate multiple applications in an enterprise.
- It enables message routing, transformation, and orchestration between systems.

---

## Why Enterprise Message Bus is Used?

- **Centralized Integration** — Connects multiple applications using one bus.
- **Message Transformation** — Converts data formats (e.g., XML → JSON).
- **Routing** — Sends messages to the correct destination.
- **Security** — Centralized authentication and authorization.
- **Monitoring & Logging** — Tracks all message flows.

---

## Popular Enterprise Message Bus Tools

- Mule ESB
- WSO2 ESB
- IBM Integration Bus
- Oracle Service Bus

---

## References

### Messaging Queues
- 📖 [Message Queues – System Design (GeeksforGeeks)](https://www.geeksforgeeks.org/system-design/message-queues-system-design/)
- 📖 [Message Queue – Wikipedia](https://en.wikipedia.org/wiki/Message_queue)
- 📖 [The Big Little Guide to Message Queues](https://sudhir.io/the-big-little-guide-to-message-queues)

### Enterprise Service Bus (ESB)
- 📖 [What is ESB? (AWS)](https://aws.amazon.com/what-is/enterprise-service-bus/)
- 📖 [What is an Enterprise Service Bus? (IBM)](https://www.ibm.com/think/topics/esb)
- 📖 [What is an ESB? (MuleSoft)](https://www.mulesoft.com/resources/esb/what-esb)
- 📖 [Enterprise Service Bus – Wikipedia](https://en.wikipedia.org/wiki/Enterprise_service_bus)
