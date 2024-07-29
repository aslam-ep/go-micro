# Go Microservices Project

This project demonstrates a microservices architecture using Go, Docker, and Kubernetes. And explore the microservices communications using REST, RPC, gRPC and RabbitMQ.

## Services

- **Broker Service**: Connects with the frontend and other services.
- **Authentication Service**: Manages user authentication using PostgreSQL.
- **Logger Service**: Logs events and errors using MongoDB.
- **Mailer Service**: Sends emails.
- **Listener Service**: Listens for events and triggers actions.