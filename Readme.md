# Apache Kafka
## Run the Application using Docker Compose
The main folder of repository contain functional `doker-compose.yml` file. Run the application using it as shown below:
```sh
$ curl -sSL https://raw.githubusercontent.com/bitnami/containers/main/bitnami/kafka/docker-compose.yml > docker-compose.yml
$ docker-compose up -d
```
or 
```sh
$ docker compose up -d
```

- Zookepper exposed port with `2181`
- Kafka's service exposed port with `9192`

## Run Apache Kafka with Confluent 
```sh
$ docker compose up -f docker-compose-confluentinc.yml
```

- Zookepper exposed port with `2181`
- Kafka's service exposed port with `29092`

## Quickstart with Kafka official document
- [Kafka Quickstart](https://kafka.apache.org/quickstart)
- [Baeldung Spring-Kafka](https://www.baeldung.com/spring-kafka)
- [Github Spring-Kafka](https://github.com/spring-projects/spring-kafka/tree/main/samples)
- [Github Baeldung Spring-Kafka](https://github.com/eugenp/tutorials/tree/master/spring-kafka)
- [Java Spring Boot: Code Example for Apache Kafka](https://docs.confluent.io/platform/current/tutorials/examples/clients/docs/java-springboot.html)
- [Go: Code Example for Apache Kafka](https://docs.confluent.io/platform/current/tutorials/examples/clients/docs/go.html)
- [Apache Kafka packaged by Bitnami](https://hub.docker.com/r/bitnami/kafka)
- [Confluent Community Docker Image for Apache Kafka](https://hub.docker.com/r/confluentinc/cp-kafka)