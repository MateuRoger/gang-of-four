## Description
**Gang of Four (GoF)** is how the authors of "Design Patterns: Elements of Reusable Object-Oriented Software " are often referred to.
A **design pattern** is the re-usable form of a solution to a design problem. The idea was introduced by the architect ***Christopher Alexander*** and has been adapted for various other disciplines, notably software engineering.

This design patterns are the most used today, so in this project we will create examples of how all GoF design patterns can be implemented.

## GoF Design Pattern Types

GoF Design Patterns are divided into three categories:

* **Creational:** The design patterns that deal with the creation of an object.
* **Structural:** The design patterns in this category deals with the class structure such as Inheritance and Composition.
* **Behavioral:** This type of design patterns provide solution for the better interaction between objects, how to provide lose coupling, and flexibility to extend easily in future.

### Creational Design Patterns

There are 5 design patterns in the creational design patterns category.
|  Pattern Name 	| Description	|
|---	|---	|
| Singleton	| The singleton pattern restricts the initialization of a class to ensure that only one instance of the class can be created. |
| Factory	| The factory pattern takes out the responsibility of instantiating a object from the class to a Factory class.|
| Abstract Factory | Allows us to create a Factory for factory classes.	|
| Builder	| Creating an object step by step and a method to finally get the object instance. 	|
| Prototype	| Creating a new object instance from another similar instance and then modify according to our requirements.	|

### Structural Design Patterns

There are 7 structural design patterns defined in the Gangs of Four design patterns book.
|  Pattern Name 	| Description	|
|---	|---	|
| Adapter | Provides an interface between two unrelated entities so that they can work together. |
| Composite | Used when we have to implement a part-whole hierarchy. For example, a diagram made of other pieces such as circle, square, triangle, etc. |
| Proxy | Provide a surrogate or placeholder for another object to control access to it. |
| Flyweight | Caching and reusing object instances, used with immutable objects. For example, string pool. |
| Facade | Creating a wrapper interfaces on top of existing interfaces to help client applications. |
| Bridge | The bridge design pattern is used to decouple the interfaces from implementation and hiding the implementation details from the client program. |
| Decorator | The decorator design pattern is used to modify the functionality of an object at runtime. |

### Behavioral Design Patterns

There are 11 behavioral design patterns defined in the GoF design patterns.
|  Pattern Name 	| Description	|
|---	|---	|
| Template Method | used to create a template method stub and defer some of the steps of implementation to the subclasses. |
| Mediator | used to provide a centralized communication medium between different objects in a system. |
| Chain of Responsibility | used to achieve loose coupling in software design where a request from the client is passed to a chain of objects to process them. |
| Observer | useful when you are interested in the state of an object and want to get notified whenever there is any change. |
| Strategy | is used when we have multiple algorithm for a specific task and client decides the actual implementation to be used at runtime. |
| Command | is used to implement lose coupling in a request-response model. |
| State | is used when an Object change it’s behavior based on it’s internal state. |
| Visitor | is used when we have to perform an operation on a group of similar kind of Objects. |
| Interpreter | defines a grammatical representation for a language and provides an interpreter to deal with this grammar. |
| Iterator | used to provide a standard way to traverse through a group of Objects. |
| Memento | The memento design pattern is used when we want to save the state of an object so that we can restore later on.  |
