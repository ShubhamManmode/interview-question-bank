Azure Service Bus Syllabus
1. Introduction to Messaging
What is messaging?
Synchronous vs asynchronous communication
Message brokers and enterprise messaging
Azure messaging services overview
Azure Service Bus
Azure Event Hubs
Azure Event Grid
Azure Queue Storage

Azure Service Bus is a fully managed enterprise message broker that provides queues and publish-subscribe topics for reliable communication between applications and services.

2. Azure Service Bus Fundamentals
Service Bus architecture
Namespace
Messaging entities
Service tiers
Basic
Standard
Premium
Use cases and benefits
3. Queues
Queue creation and configuration
Sending messages
Receiving messages
Peek Lock mode
Receive and Delete mode
FIFO processing
Queue properties
4. Topics and Subscriptions
Publish/Subscribe pattern
Creating topics
Creating subscriptions
Subscription filters
SQL filters
Correlation filters
Message routing
5. Message Handling
Message structure
Message properties
Message serialization (JSON/XML)
Scheduled messages
Deferred messages
Message expiration (TTL)
Dead-letter queues (DLQ)
6. Reliability Features
Duplicate detection
Message sessions
Transactions
Auto-forwarding
Retry mechanisms
Message ordering
7. Security
Shared Access Signature (SAS)
Microsoft Entra ID authentication
Role-Based Access Control (RBAC)
Secure communication using TLS

Microsoft Learn includes authentication with SAS and Microsoft Entra ID as core Service Bus security topics.

8. Development with Azure Service Bus
Azure SDK setup
.NET implementation
Java implementation
Python implementation
Node.js implementation
Sending and receiving messages programmatically
9. Monitoring and Troubleshooting
Azure Monitor integration
Metrics and logs
Diagnostic settings
Message tracking
Troubleshooting common exceptions

Monitoring through Azure Monitor is part of the official Service Bus guidance.

10. Integration Scenarios
Azure Functions + Service Bus
Logic Apps + Service Bus
Microservices communication
Event-driven architecture
Hybrid cloud integration
11. Advanced Concepts
AMQP protocol
JMS 2.0 support
Sessions and workflows
Enterprise integration patterns
Scaling and performance optimization

Azure Service Bus supports queues, topics/subscriptions, transactions, sessions, and JMS-based messaging scenarios.

12. Hands-On Labs
Create a Service Bus Namespace.
Create a Queue.
Send and Receive Messages.
Create Topics and Subscriptions.
Configure Filters.
Implement Dead-Letter Queue Handling.
Integrate with Azure Functions.
Monitor Service Bus Metrics.
Recommended Learning Path (Beginner to Advanced)
Azure Fundamentals (AZ-900)
Messaging Concepts
Azure Service Bus Basics
Queues
Topics & Subscriptions
Security & Authentication
Development with SDKs
Monitoring & Troubleshooting
Advanced Messaging Patterns
Real-world Projects
