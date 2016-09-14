title: 'Build your Microservices with ZeroMQ'
subtitle:
speaker: floris-bruynooghe
---
Microservices is the popular term for the trend to build backend
architectures as a number of smaller independent processes.  As an
evolution from the Service Oriented Architecture the core aims are to
create independent services which are easy to operate and even replace
while all of them together compose into providing the business logic
required for your application.

While it is rather common for microservices to choose JSON over HTTP
to communicate with each other, this is purely an implementation
choice.  HTTP is a protocol using a strict request-response format,
this can become a little burdensome when needing to deal with
asynchronous requests and forces some architectural decisions to be
not as ideal as they could be.  ZeroMQ has more flexible communication
patterns allowing for easier mapping of real-life interactions between
services.  Coupled with an easy to use asynchronous user-level API and
very fast underlying communication on persistent TCP connections
ZeroMQ is a rather attractive transport to build your microservices
based applications in.

This talk will show how to use ZeroMQ within Python to build your
microservices.  It will show the benefits of ZeroMQ's asynchronous
API, common usage patterns and how to handle backpressure.
Furthermore different communication patterns will be explored and the
impact this has on how to simplify the overall architecture using
these patterns.
