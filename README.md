# Spring-Kafka Event-Driven Architecture

![Overall Architecture](/kafka_event_driven_microservices.png)

## Repository Description

This repository showcases an event-driven architecture implemented with Spring Boot and Apache Kafka. In this architecture, the OrderService, StockService, and EmailService microservices operate independently and communicate via event-driven messaging.

- **OrderService:** A producer application that generates events and sends them to a Kafka message broker.
- **StockService:** A consumer microservice responsible for processing events related to stock management.
- **EmailService:** Another consumer microservice that handles email notifications based on events.

This repository contains code, configuration, and resources for building and deploying this event-driven system. It serves as a practical example for those interested in implementing event-driven architectures with Spring Boot and Kafka. 

Feel free to customize the description to better suit your specific project's goals and scope.