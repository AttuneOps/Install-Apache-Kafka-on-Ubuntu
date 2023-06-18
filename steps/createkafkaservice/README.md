In the `[Unit]` section, it is stated that this unit file has a dependency 
on `zookeeper.service`, ensuring that Zookeeper is automatically started when 
the Kafka service is initiated.

The `[Service]` section configures systemd to use the 
`kafka-server-start.sh` and `kafka-server-stop.sh` shell scripts for 
starting and stopping the Kafka service. It further specifies that if 
Kafka terminates unexpectedly, it should be restarted automatically.