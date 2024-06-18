# gRPC-Python-microservices


## About This Project
Using python built a gRPC server.

- start server
  
![server](https://github.com/BiChong-Jin/gRPC-Python-microservices/assets/130134152/433aa08e-2e3f-486d-a522-48c44655584b)
- start client
  
![client](https://github.com/BiChong-Jin/gRPC-Python-microservices/assets/130134152/48b77d2c-9d58-40ae-85bf-4b140887cab3)



## What is gRPC

gRPC (gRPC Remote Procedure Calls) is an open-source remote procedure call (RPC) framework developed by Google. It is designed to facilitate communication between different services, making it easier to build connected systems.

Key Features of gRPC
- High Performance:

gRPC uses HTTP/2 for transport, which provides lower latency and more efficient use of network resources compared to HTTP/1.x.
It supports multiplexing multiple requests over a single connection, reducing overhead.
- Language-agnostic:

gRPC supports multiple programming languages, allowing services written in different languages to communicate seamlessly.
Officially supported languages include C++, Java, Python, Go, C#, Node.js, Ruby, PHP, and more.
- Protocol Buffers:

gRPC uses Protocol Buffers (protobuf) as its interface definition language (IDL). Protobuf is a binary serialization format that is efficient and language-neutral.
The service and message definitions are written in .proto files, which are then compiled into code for the target languages.
- Bi-directional Streaming:

gRPC supports different types of RPCs: unary (single request/response), server streaming, client streaming, and bi-directional streaming.
This flexibility allows for real-time data exchange and efficient handling of long-lived connections.
- Pluggable Authentication:

gRPC supports pluggable authentication mechanisms, including SSL/TLS for encryption and token-based authentication.
It can be integrated with existing authentication systems to secure communication.

To learn more about gRPC, take a look at the following resources:

- [gRPC Homepage](https://grpc.io/)


