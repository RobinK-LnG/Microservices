# Application Architecture Patterns

These patterns are primarily concerned with the structure and organization of software applications.

- **Domain-Driven Design (DDD)**: Used for complex domains where the business logic and requirements are evolving and intricate.
- **Onion Architecture**: Provides a way to keep the domain model at the center of the application, promoting loose coupling and separation of concerns; useful for complex applications where the domain logic needs protection from changes in external layers.
- **Hexagonal Architecture (Ports and Adapters)**: Similar to Onion Architecture, this pattern aims to isolate the core logic of the application from external influences and frameworks. It is particularly useful in systems that require multiple channels of interaction or input/output devices.
- **CQRS (Command Query Responsibility Segregation)**: Used when different aspects of the system have divergent requirements regarding data read and write operations, enhancing performance and scalability.
- **Event-Driven Architecture**: Suitable for applications where decoupled, asynchronous processing of events is needed.
