# Kogito Quickstarts

A collection of quickstarts for Kogito that illustrates various uses case covered.

Since Kogito aims at supporting both Quarkus and SpringBoot each quickstart should provide both type of projects.

## Kogito hello world with scripts

shows most basic use of processes to build up a hello world example

* [on Quarkus](kogito-scripts-quarkus)
* [on SpringBoot](kogito-scripts-springboot)


## Kogito with business rules

shows integration between processes and rules.

* [on Quarkus](kogito-business-rules-quarkus)
* [on SpringBoot](kogito-business-rules-springboot)


## Kogito with Kafka

shows how message start and end events can be easily used to integrate with Apache Kafka to consume where
message name is the Kafka topic and the payload is mapped to process variable. Uses custom types
that are serialized into JSON.

* [on Quarkus](kogito-kafka-quickstart-quarkus)
* [on SpringBoot](kogito-kafka-quickstart-springboot)

## Kogito with Infinispan persistence

shows long running processes with Infinispan persistence so the state of process instances can
be preserved across service restarts.

* [on Quarkus](kogito-infinispan-persistence-quarkus)
* [on SpringBoot](kogito-infinispan-persistence-springboot)

## Kogito with service invocation

shows how easy it is to use local services to be invoked from within process. Allows easy and readable
service invocation use cases to be covered.

* [on Quarkus](kogito-service-calls-quarkus)
* [on SpringBoot](kogito-service-calls-springboot)

## Kogito with REST call

shows REST service invocation and parsing data back to an object instance used as process variable.

* [on Quarkus](kogito-service-rest-call-quarkus)
* [on SpringBoot](kogito-service-rest-call-springboot)



## Contribution

Everyone is encouraged to contribute to this quickstarts by

* trying it out and providing feedback and ideas for improvement
* create new quickstarts
* blogging about it
* using it on conferences and workshops
