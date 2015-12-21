# springboot-rabbitmq-tutorial
Following tutorial at http://spring.io/guides/gs/messaging-rabbitmq/

## Rabbit MQ with docker

__Note__: you need to have (docker installed)[https://docs.docker.com/linux/started/]

To start Rabbit host, just run:

    $ docker-compose up -d

## run

    $ mvn spring-boot:run

On windows and Mac, you need to specify the RabbitMQ Docker Host, run it with:

    $ mvn spring-boot:run -Dspring.rabbitmq.host=192.168.99.100

## Rabbit MQ Manager

  Access it in http://localhost:15672/ or http://192.168.99.100:15672/ if in windows/mac