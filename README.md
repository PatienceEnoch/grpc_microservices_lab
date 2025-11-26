# gRPC Microservices Lab (Python)

This project demonstrates a minimal gRPC microservice system using Python, Protocol Buffers, and gRPC.

## Overview
The lab contains two components:

1. A server implementing a `GreeterService`.
2. A client that sends a request to the server and prints the response.

Both components communicate using gRPC over port 50051.

## Project Structure
grpc-microservices-lab/
    proto/
        greeter.proto          # Service contract
    server/
        app.py                 # gRPC server implementation
    client/
        app.py                 # gRPC client implementation
    greeter_pb2.py             # Generated message classes
    greeter_pb2_grpc.py        # Generated gRPC classes
    README.md

## How it Works
1. The service contract is defined in `proto/greeter.proto`.
2. Python gRPC tools generate the files:
   - `greeter_pb2.py`
   - `greeter_pb2_grpc.py`
3. The server (`server/app.py`) listens for incoming RPC requests.
4. The client (`client/app.py`) sends a request and receives a reply from the server.

## Running the Server

## Running the Client

## Concepts Practiced
- Defining service contracts using Protocol Buffers
- Generating client and server code from `.proto` files
- Building minimal microservice components
- Understanding gRPC communication flow
