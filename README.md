# Zeus Cloud Team 
## Kafka Bootcamp 2017
---
### Preparing for the bootcamp
The bootcamp will start off with an introductory talk about Kafka which will describe the 4 scenarios included in the bootcamp and then launch into a session of hands on development.  People will be asked to form 4 - 6 person groups.  Groups can collaborate and work on the scenarios together.  

#### Environment
The bootcamp will be done on your personal laptop, connecting to an instance of Confluent Cloud (Apache Kafka hosted on AWS).  There is starter code to get you going.  The starter code is a [starter producer](https://github.com/Zeus-Cloud-Team/kafka-producer-starter), [starter consumer](https://github.com/Zeus-Cloud-Team/kafka-consumer-starter) and [instructions to set up the Confluent Cloud CLI tool](https://github.com/Zeus-Cloud-Team/confluent-cloud-cli) for administering your topics on Confluent Cloud (called ccloud cli).

#### Preparing your laptop
1. [Make sure your laptop has a JDK more recent than 1.8.0_101](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) , without at least this version you won't be able to connect to Confluent Cloud.  In addition to this version being installed it should also be the active java runtime for your maven (see step 3) and your IDE (see step 2)
2. Your laptop should have your favorite IDE for java development (Intellij, Eclipse, Netbeans)
3. Have command line maven [installed](https://maven.apache.org/download.cgi) and available for use on the command line 
1. Alternatively, you could [install and run Kafka locally](https://www.confluent.io/download/) and use that during the bootcamp as long as you're not using windows, there's nothing special about Confluent Cloud Kafka that you can't get by running locally.  

#### Preparing to get interact with Confluent Cloud
1. Get connection details and credentials from the Cloud team (bootstrap servers list, schema registry server, api key(username), api secret(password))
2. [Install ccloud](https://github.com/Zeus-Cloud-Team/confluent-cloud-cli), you'll need the information from step 1 to connect ccloud cli to the instance of Confluent Cloud we're using.  Once you connect familiarize yourself with administration of topics.
3. You will have to follow these guidelines when using ccloud cli to administer Confluent Cloud Kafka 
   * If part of a team select one person from the team and use that persons first name to prefix all topics you interact with
   * NEVER modify a topic that you do not own, or are not working on as part of a team
**NOTE** There is only 1 account, so all participants will have the ability to modify every other topic.  Like Uncle Ben said, with great power comes great responsibility.

#### Preparing your brain
This bootcamp is not aimed at people who are not at all familiar with Kafka.  Coming into this event you should be armed with knowledge.

1. [Kafka - The Definitive Guide](https://www.confluent.io/wp-content/uploads/confluent-kafka-definitive-guide-complete.pdf)
2. [You should know about Avro and schemas](https://www.confluent.io/blog/avro-kafka-data/)
2. Reach out to the Cloud team to get more recommended reading material to prepare yourself
1. [Download Kafka to run locally](https://www.confluent.io/download/) if you are on a non windows machine (don't try to run Kafka on windows), and try out the scenarios listed here.

### The scenarios
### 1 - Event Sourcing
![Event Sourcing Diagram](pics/ca-kafka-event-sourcing.svg)