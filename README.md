## SOLID Principles

### Single Responsibility Principle:
* Every software component should have one and only one responsibility/reason to change. Swiss knife is an anti-example.

* Cohesion is the degree to which the various part of software components are related.

* Higher cohesion helps attain better adherence to SRP

* Coupling is defined as level of inter dependency between various software components

* Always aim for higher cohesion and loose coupling

### Open/Closed Principle:
* Software component should be closed for modification, but open for extension
* Benefits
    * Ease of adding features
    * Less to minimal cost in developing and testing software
    * It often required decoupling which in turn automatically follows SRP

### Liskov Substitution Principle:
* Objects should be replaceable with their subtypes without affecting correctness of the program.
* If you use instanceof operator, you are most probably this principle
### Interface Segregation Principle:
* No client should be forced to depend on methods it does not use
* Techniques to identify violation of ISP
    * Fat interfaces
    * Interfaces with Low cohesion
    * Empty Implementation of methods



### Dependency Inversion Principle:
* High level module should not depend on low level module. Both should depend on abstraction
