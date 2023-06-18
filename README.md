



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# Install Apache Kafka on Ubuntu






# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

To clone this project into your own instance of Attune, follow the
[Clone a GIT Project How To Instructions](https://servertribe-attune.readthedocs.io/en/latest/howto/design_workspace/clone_project.html).




## Blueprints

This Project contains the following Blueprints.



### Install Apache Kafka on Ubuntu 20.04

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




## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Ubuntu Node | Linux/Unix Node | `ubuntunode` |  |
| Sudo User | Linux/Unix Credential | `sudouser` |  |
| User | Linux/Unix Credential | `user` |  |
| kafka User | Linux/Unix Credential | `kafkauser` |  |
| kafka Sudo User | Linux/Unix Credential | `kafkasudouser` |  |
| kafka Binaries URL | Text | `kafkabinariesurl` | Get the kafka Binaries URL here: https://downloads.apache.org/kafka/ |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**
