Experiment 12: CRUD Operations using Spring Boot REST API

What is CRUD?
Create, Read, Update, Delete — the basic operations for managing persistent data.

What are CRUD operations?
Create (insert), Read (retrieve), Update (modify), Delete (remove) resource records.

Which HTTP methods are used for CRUD?
POST for Create, GET for Read, PUT/PATCH for Update, DELETE for Delete.

What is JPA?
Java Persistence API, a specification for object-relational mapping and data persistence in Java.

What is Hibernate?
A popular JPA implementation that provides ORM functionality for mapping Java objects to database tables.

What is JpaRepository?
A Spring Data interface that provides CRUD and pagination methods for JPA entities.

What is @Entity?
A JPA annotation that marks a class as a persistent entity mapped to a database table.

What is @Id?
Marks a field as the primary key of an entity.

What is @GeneratedValue?
Specifies that the primary key value should be generated automatically (strategy can be defined).

What is @Service?
A Spring stereotype annotation indicating a service-layer component containing business logic.

What is @Repository?
A Spring stereotype for persistence-layer components; it also translates persistence exceptions into Spring exceptions.

What is @PathVariable?
Binds a URI template variable to a method parameter in a controller (e.g., /items/{id}).

What is @RequestMapping?
Maps HTTP requests to handler methods or classes for specified paths and methods.

What is database connectivity?
The configuration and connection between an application and a database (via JDBC, connection pools, drivers).

What is the three-layer architecture in Spring Boot?
Presentation (controllers), Service (business logic), Repository/DAO (data access) layers to separate concerns.