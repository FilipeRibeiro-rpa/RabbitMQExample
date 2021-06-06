# RabbitMQ Example

This project was created to show an example of how RabbitMQ software can be implemented in a microservices architecture.

# Prerequisites

Before running the services it is necessary to install the docker on the machine. After installation, you need to run the code below to start a RabbitMQ server:

      docker run -d --hostname my-rabbit --name some-rabbit -p 5672: 5672 rabbitmq: 3-management

#  Project

Two console app projects were created in Aps Net Core, the first one called producer.message, which will be responsible for publishing messages in RabbitMQ, the second project called consumer.message is responsible for reading messages in the RabbitMQ queue.
