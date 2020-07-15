# ActiveMQ

http://activemq.apache.org

Flexible & Powerful Open Source Multi-Protocol Messaging

Apache ActiveMQ™ is the most popular open source, multi-protocol, Java-based messaging server. It supports industry standard protocols so users get the benefits of client choices across a broad range of languages and platforms. Connectivity from C, C++, Python, .Net, and more is available. Integrate your multi-platform applications using the ubiquitous AMQP protocol. Exchange messages between your web applications using STOMP over websockets. Manage your IoT devices using MQTT. Support your existing JMS infrastructure and beyond. ActiveMQ offers the power and flexibility to support any messaging use-case.

There are currently two "flavors" of ActiveMQ available - the "classic" 5.x broker and the "next generation" Artemis broker. Once Artemis reaches a sufficient level of feature parity with the 5.x code-base it will become ActiveMQ 6. Initial migration documentation is available.

## ActiveMQ 5 "Classic"

Long established, endlessly pluggable architecture serving many generations of applications.

* JMS 1.1 with full client implementation including JNDI
* High availability using shared storage
* Familiar JMS-based addressing model
* "Network of brokers" for distributing load
*  KahaDB & JDBC options for persistence

## ActiveMQ Artemis

High-performance, non-blocking architecture for the next generation of event-driven messaging applications.

* JMS 1.1 & 2.0 with full client implementation including JNDI
* High availability using shared storage or network replication
* Simple & powerful protocol agnostic addressing model
* Flexible clustering for distributing load
* Advanced journal implementations for low-latency persistence as well as JDBC
* High feature parity with ActiveMQ 5 to ease migration

### Protect your data & Balance your Load

ActiveMQ provides many advanced features including message load-balancing and high-availability for your data. Multiple connected "master" brokers can dynamically respond to consumer demand by moving messages between the nodes in the background. Brokers can also be paired together in a master-slave configuration so that if a master fails then the slave takes over ensuring clients can get to their important data and eliminating costly downtime.

 ### Easy Enterprise Integration Patterns

Enterprise Integration Patterns describe the various ways in which multiple applications generally interact and integrate with each other. Aysnchronous messaging is at the heart of this integration, and ActiveMQ makes it easy to leverage these patterns via Apache Camel routes deployed directly on the broker.

### Flexible Deployment

ActiveMQ is most commonly deployed as a standalone process. This option isolates ActiveMQ from any particular application and provides maximum flexibility for resource allocation and management. However, ActiveMQ can be configured to have a very small footprint which makes it viable to embed it within your application. This option can provide an application with simple, powerful messaging semantics and also allow easy message exchange with other applications.
