# ActiveMQ

http://activemq.apache.org

Flexible & Powerful Open Source Multi-Protocol Messaging
灵活而强大的开源多协议消息中间件

Apache ActiveMQ™ is the most popular open source, multi-protocol, Java-based messaging server. It supports industry standard protocols so users get the benefits of client choices across a broad range of languages and platforms. Connectivity from C, C++, Python, .Net, and more is available. Integrate your multi-platform applications using the ubiquitous AMQP protocol. Exchange messages between your web applications using STOMP over websockets. Manage your IoT devices using MQTT. Support your existing JMS infrastructure and beyond. ActiveMQ offers the power and flexibility to support any messaging use-case.

Apache ActiveMQ™是最流行的开源，多协议，基于Java的消息传递服务器。它支持行业标准协议，因此用户可以通过多种语言和平台从客户选择中受益。可以使用C，C ++，Python，.Net等进行连接。使用无处不在的AMQP协议集成您的多平台应用程序。在Websocket上使用STOMP在Web应用程序之间交换消息。使用MQTT管理您的IoT设备。支持您现有的JMS基础结构及其他。ActiveMQ提供了强大的功能和灵活性来支持任何消息传递用例。

There are currently two "flavors" of ActiveMQ available - the "classic" 5.x broker and the "next generation" Artemis broker. Once Artemis reaches a sufficient level of feature parity with the 5.x code-base it will become ActiveMQ 6. Initial migration documentation is available.

ActiveMQ当前有两种“风味”可用-“经典” 5.x代理和“下一代” Artemis代理。一旦Artemis与5.x代码库达到足够的功能奇偶校验级别，它将变为ActiveMQ6。可以使用初始迁移文档。

## ActiveMQ 5 "Classic"

Long established, endlessly pluggable architecture serving many generations of applications.

长期建立的，可无限插入的体系结构，可服务于多代应用程序。

* JMS 1.1 with full client implementation including JNDI
* High availability using shared storage
* Familiar JMS-based addressing model
* "Network of brokers" for distributing load
* KahaDB & JDBC options for persistence

* 具有完整客户端实现（包括JNDI）的JMS 1.1
* 使用共享存储实现高可用性
* 熟悉的基于JMS的寻址模型
* “经纪人网络”用于分配负载
* KahaDB和JDBC持久性选项

## ActiveMQ Artemis

High-performance, non-blocking architecture for the next generation of event-driven messaging applications.

高性能，无阻塞的体系结构，用于下一代事件驱动的消息传递应用程序。

* JMS 1.1 & 2.0 with full client implementation including JNDI
* High availability using shared storage or network replication
* Simple & powerful protocol agnostic addressing model
* Flexible clustering for distributing load
* Advanced journal implementations for low-latency persistence as well as JDBC
* High feature parity with ActiveMQ 5 to ease migration

* 具有完整客户端实现（包括JNDI）的JMS 1.1和2.0
* 使用共享存储或网络复制实现高可用性
* 简单而强大的协议不可知寻址模型
* 灵活的集群以分配负载
* 用于低延迟持久性和JDBC的高级日志实现
* 与ActiveMQ 5的高功能奇偶校验可简化迁移

### Protect your data & Balance your Load

ActiveMQ provides many advanced features including message load-balancing and high-availability for your data. Multiple connected "master" brokers can dynamically respond to consumer demand by moving messages between the nodes in the background. Brokers can also be paired together in a master-slave configuration so that if a master fails then the slave takes over ensuring clients can get to their important data and eliminating costly downtime.

ActiveMQ提供了许多高级功能，包括消息负载均衡和数据的高可用性。多个连接的“主”代理可以通过在后台节点之间移动消息来动态响应消费者需求。代理还可以在主从配置中配对在一起，这样，如果主服务器发生故障，则从服务器将接管确保客户端可以获取其重要数据并消除代价高昂的停机时间。

 ### Easy Enterprise Integration Patterns

Enterprise Integration Patterns describe the various ways in which multiple applications generally interact and integrate with each other. Aysnchronous messaging is at the heart of this integration, and ActiveMQ makes it easy to leverage these patterns via Apache Camel routes deployed directly on the broker.

企业集成模式描述了多个应用程序通常相互交互和集成的各种方式。异步消息传递是此集成的核心，ActiveMQ使通过直接部署在代理上的Apache Camel路由轻松利用这些模式。

### Flexible Deployment

ActiveMQ is most commonly deployed as a standalone process. This option isolates ActiveMQ from any particular application and provides maximum flexibility for resource allocation and management. However, ActiveMQ can be configured to have a very small footprint which makes it viable to embed it within your application. This option can provide an application with simple, powerful messaging semantics and also allow easy message exchange with other applications.

ActiveMQ最通常部署为独立过程。此选项将ActiveMQ与任何特定应用程序隔离开来，并为资源分配和管理提供最大的灵活性。但是，可以将ActiveMQ配置为具有很小的占用空间，使其能够嵌入到您的应用程序中。此选项可以为应用程序提供简单，强大的消息传递语义，还可以轻松与其他应用程序交换消息。
