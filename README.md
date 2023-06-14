# Tiktok-2023-Backend-Assignment-


## Introduction
This project is part of Tiktok Tech Immersion Programme 2023's Backend Assignment. It is designed to process HTTP requests and responses through an HTTP server, while the majority of the business logic is handled by microservices residing in the RPC server. The RPC server communicates with the HTTP server locally, and external clients cannot directly access the RPC server. The project utilizes a Redis server to store and retrieve messages.

## Project Requirements
The following are the requirements for the project:

Implement an HTTP server to process HTTP requests and responses.
Utilize a Redis server as a datastore for storing messages.
Implement handlers in the RPC server to send and pull messages.
Setup and configure the Redis server.
Edit the docker-compose.yml file to add a Redis server.
Setup a Redis client in the RPC server.

## API Specifications
The project follows the API specifications defined in idl_http.proto. It will send and pull messages through a Redis server.
