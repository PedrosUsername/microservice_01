# Microservice based app piece - microservice 01

#### Index

* [Gateway](https://github.com/PedrosUsername/gateway)
* [Service Discovery](https://github.com/PedrosUsername/service_discovery)
* [Config Server](https://github.com/PedrosUsername/config_server)
* [Microservice 02](https://github.com/PedrosUsername/microservice_02) <--(voce esta aqui)
* [Microservice 01](https://github.com/PedrosUsername/microservice_01)

## microservice 01

O microservice 01, é a implementação de um CR__ do sistema de um catálogo de produtos, criado
aqui para fins didáticos.

## Esse projeto foi feito com Spring Boot:

Inicie-o no seu sistema com o comando

```shell script
$ ./gradlew bootRun
```

Com o Elasticsearch e o [Config Server](https://github.com/PedrosUsername/config_server)
em funcionamento, recupere um registro (ou null) com:

```shell script
$ curl -X GET localhost:8081/product/1
```

## O projeto foi desenvolvido e testado sob as seguintes condições:

* Java 8;
* Gradle 7.1.1;
* Elasticsearch 7.14.0;
* Docker 20.10.8
* Linux 5.4.0-81-generic amd64
* Intellj IDEA Community Edition;
* Controle de versão GIT;
* GitHub;
