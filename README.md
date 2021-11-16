# Messenger_RabbitMQ

## Principle 

Asynchronous messaging application with RabbitMQ

### Table of content

[Ressources](#Ressources)

## Ressources

* The [official docker image](https://registry.hub.docker.com/_/rabbitmq/) of RabbitMQ
* The Picka Python client (**version 1.2.0**): `pip install pika --upgrade`

To launch the RabbitMQ docker, open a terminal and run `docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management`