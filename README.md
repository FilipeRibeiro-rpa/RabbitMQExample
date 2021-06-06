# RabbitMQ Example

This project was created to show example of as software RabbitMQ can be implement in a microservices arquicteture.

# Pré-Requisitos

Before of execute the services is necessary docker install in the machine. After that of install to need execute code:

    docker run -d --hostname my-rabbit --name some-rabbit -p 5672:5672  rabbitmq:3-management

# Project Estruture

Foram criados dois projetos console app em net core, o primerio chamdao producer, o qual será responsável por publicar mensagens no RabbitMQ, o segundo segundo projeto chamado consumer é responsável por ler as mensagens na fila do RabbitMQ.
