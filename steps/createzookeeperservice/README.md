Create the `zookeeper` unit file.

In the `[Unit]` section, it is defined that Zookeeper depends on the 
readiness of networking and the filesystem to initiate.

The `[Service]` section instructs systemd to utilize the 
`zookeeper-server-start.sh` and `zookeeper-server-stop.sh` shell scripts 
for initiating and terminating the service. Additionally, it configures 
Zookeeper to be automatically restarted in case of abnormal termination.