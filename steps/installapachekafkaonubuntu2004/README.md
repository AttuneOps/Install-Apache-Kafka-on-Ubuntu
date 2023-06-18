This instruction aims to take you on a journey of installing, configuring, 
and hardening Apache Kafka.

Apache Kafka is a widely adopted distributed message broker specifically 
designed to handle large amounts of real-time data. Its scalability and fault 
tolerance make it a preferred choice for building robust systems. In 
comparison to other message brokers such as ActiveMQ and RabbitMQ, Kafka 
stands out with its remarkable throughput capabilities. While its primary 
usage revolves around publish/subscribe messaging, it is also extensively 
utilised for log aggregation due to its ability to persistently store 
published messages.

In a publish/subscribe messaging system, one or more producers can publish 
messages without having to worry about the number of consumers or their 
specific message processing methods. Subscribed clients automatically 
receive notifications about updates and the arrival of new messages. This 
approach proves to be more efficient and scalable compared to systems where 
clients need to poll at regular intervals to check for the availability of 
new messages.

To successfully follow these instructions, you will need an Ubuntu 20.04 
server equipped with a minimum of 4 GB of RAM. Additionally, ensure that you 
have a non-root user configured with `sudo` privileges.

Another prerequisite is the installation of OpenJDK 11 on your server. You 
can easily accomplish this by following our instructions on 
[Installing Java on Ubuntu](https://www.attuneautomation.com/Install-Java-on-Ubuntu/)
.