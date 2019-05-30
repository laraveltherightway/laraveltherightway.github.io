---
isChild: true
anchor:  programming_paradigms
---

## Programming Paradigms {#programming_paradigms_title}


As you go through Laravel documentation, you'll encounter a lot of buzz words such as service provider, dependency injection, IoC container, HTTP Resource and so on.

It is a good idea to get some background of these concepts first before diving into using  the framework, so you will be able to make sense why the framework is designed this way.


### Service Provider

Generally, a **Service** is a well-known set of programming interfaces and classes that provide access to some specific application functionality or feature. While a **Service Provider Interface** is an interface or abstract class that acts as a proxy or an endpoint to the service.
So by definition, a **Service Provider** is a specific implementation of the SPI. The Service Provider contains one or more concrete classes that implement or extends the service type.

### Dependency Injection

is a technique whereby one object (or static method) supplies the dependencies of another object. A dependency is an object that can be used (a service). An injection is the passing of a dependency to a dependent object (a client) that would use it. The service is made part of the client's state. Passing the service to the client, rather than allowing a client to build or find the service, is the fundamental requirement of the pattern.


### Inversion Of Control

IoC inverts the flow of control as compared to traditional control flow. In IoC, custom-written portions of a computer program receive the flow of control from a generic framework. A software architecture with this design inverts control as compared to traditional procedural programming: in traditional programming, the custom code that expresses the purpose of the program calls into reusable libraries to take care of generic tasks, but with inversion of control, it is the framework that calls into the custom, or task-specific code

### Command Bus Pattern

The Command Bus pattern is trying to decouple as much as it can the controller, the framework itself to the domain layer, which should be totally unaware of application’s upper layer. It keeps the user interface logic separated from your models.


### SOLID Principle

* Single responsibility principle - 
A class should only have a single responsibility, that is, only changes to one part of the software's specification should be able to affect the specification of the class.
* Open–closed principle - "Software entities ... should be open for extension, but closed for modification."
* Liskov substitution principle - "Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program." See also design by contract.
* Interface segregation principle - "Many client-specific interfaces are better than one general-purpose interface."
* Dependency inversion principle -  One should "depend upon abstractions, not concretions."

### Domain Driven Design

is an approach to software development for complex needs by connecting the implementation to an evolving model. The premise of domain-driven design is the following:

* placing the project's primary focus on the core domain and domain logic;
* basing complex designs on a model of the domain;
* initiating a creative collaboration between technical and domain experts to iteratively refine a conceptual model that addresses particular domain problems.