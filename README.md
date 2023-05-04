# learning-design-patterns
Short notes on explanations & code examples I've taken whilst learning about design patterns.

***Design Principles*** : guidelines to be applied when designing classes/applications, which help us to achieve software design that is easy to extend, understand, maintain & test.

## SOLID Design Principles
**S**ingle Responsibility: Each module should have one and only one reason to change (a class should have only one responsibility)

**O**pen-closed

**L**iskov Substitution: subtypes must be substitutable for their base type (square is not a subtype of rectangle example (equal sides -> one parameter hence does not correctly implement base class methods)

**I**nterface Segregation: clients should not be forced to depend on methods they do not use. Split large interfaces into smaller ones. Inherit multiple if required. 

**D**ependency Inversion: High-level modules should not depend on low-level modules. Both should depend on abstraction. 


## Types of Design Patterns
**Creational**: for class-creation or object-creational patterns

**Structural**: class & object composition 

**Behavioural**: communication between objects 


### Creational 
##### Builder Pattern
##### Simple Factory Pattern
##### Singleton Pattern



### Structural 
##### Adapter
##### Bridge
##### Decorator
##### Composite
##### Proxy


### Behavioural 
##### Command
##### Interpreter
##### Mediator
##### Memento
##### Chain of Responsibility








## *References*:
- Udemy: Java Design Patterns & SOLID Design Principles by Coffee Powered Crew
