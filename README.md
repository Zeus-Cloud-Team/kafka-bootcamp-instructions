# Zeus Cloud Team 
## Kafka Bootcamp 2017
---
### 1. Preparing for the bootcamp
The bootcamp will start off with an introductory talk about Kafka which will describe the 4 scenarios included in the bootcamp and then launch into a session of hands on development.  People will be asked to form 4 - 6 person groups.  Groups can collaborate and work on the scenarios together.  

#### Environment
The bootcamp will be done on your personal laptop, connecting to an instance of Confluent Cloud (Apache Kafka hosted on AWS).  There is starter code to get you going.  The starter code is a [starter producer](https://github.com/Zeus-Cloud-Team/kafka-producer-starter), [starter consumer](https://github.com/Zeus-Cloud-Team/kafka-consumer-starter) and [instructions to set up the Confluent Cloud CLI tool](https://github.com/Zeus-Cloud-Team/confluent-cloud-cli) for administering your topics on Confluent Cloud (called ccloud cli).

#### Preparing your laptop
1. [Make sure your laptop has a JDK >= 1.8.0_101(http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) , without at least this version you won't be able to connect to Confluent Cloud.  In addition to this version being installed it should also be the active java runtime for your maven (see step 3) and your IDE (see step 2)
2. Your laptop should have your favorite IDE for java development (Intellij, Eclipse, Netbeans)
3. Have command line maven [installed](https://maven.apache.org/download.cgi) and available for use on the command line 
