To enable common service actions for Kafka, such as starting, stopping, and 
restarting, it is necessary to create systemd unit files. These files ensure 
that Kafka operates consistently with other Linux services.

Zookeeper plays a crucial role in managing the cluster state and 
configurations for Kafka. It is a widely used tool in various distributed 
systems, and you can find detailed information about it in the official 
Zookeeper documentation. For this purpose, you will utilize Zookeeper as 
a service with the created unit files.