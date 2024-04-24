# Database Design Patterns
These patterns deal with database architecture and strategies to handle data in distributed systems.

- **Database per Service**: Each microservice manages its own database, promoting data encapsulation and service independence.
- **Shared Database**: Multiple services share the same database, reducing data redundancy but increasing coupling.
- **Saga Pattern**: Manages long-running business processes and ensures data consistency across services in a transactional manner.