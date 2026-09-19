# gRPC Microservices Lab

**Status: early learning exercise / partial prototype**

I started this repository while learning how gRPC uses Protocol Buffers to define contracts between services.

The current repository contains the service contract in:

~~~text
proto/greeter.proto
~~~

It does **not** currently contain the complete client/server implementation described in my earlier notes, so I am keeping this README accurate to what is actually committed.

## What I practiced

- Defining an RPC service with Protocol Buffers
- Separating an interface contract from an implementation
- Understanding generated client/server stubs
- Comparing RPC-style communication with ordinary HTTP APIs

## Why I am keeping this repo

This is not one of my current portfolio projects. I am keeping it public as a record of an earlier learning step rather than presenting it as a finished microservices system.

My more complete current projects are:

- [Network Flight Recorder](https://github.com/PatienceEnoch/network-flight-recorder)
- [Mini Internet](https://github.com/PatienceEnoch/mini-internet)
- [Shipment Tracker](https://github.com/PatienceEnoch/shipment-tracker)
