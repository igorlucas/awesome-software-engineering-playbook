# Architecture

This section explores how to structure software, divide responsibilities, and make architecture decisions that fit a system's business and operational constraints.

## Topic Map

### Application Structure and Boundaries

- Layered Architecture
- Hexagonal Architecture (Ports and Adapters)
- Clean Architecture
- Vertical Slice Architecture
- Domain-Driven Design (DDD)
- Modular Monoliths

### Deployment and Service Topology

- Monoliths vs. Microservices
- Service decomposition and ownership
- Distributed systems fundamentals

### Communication and Consistency

- Event-Driven Architecture
- Synchronous and asynchronous integration
- CQRS and Event Sourcing
- Transactions, the Outbox pattern, Sagas, and eventual consistency

These topics address different dimensions. Clean and Hexagonal Architecture describe dependency boundaries; a modular monolith or microservices describe deployment and ownership boundaries; Event-Driven Architecture describes communication and workflow choices. They can be combined, but each adds its own trade-offs.

## Start Here

- [Clean Architecture: A Practical Guide](clean-architecture.md)

The guide focuses on real-world trade-offs, enterprise scenarios, and examples in .NET, Java, and other ecosystems.

