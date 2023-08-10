## Acronym
S - Single Responsibility Principle
O - Open Closed Principle
L - Liskov Substitution Principle
I - Interface Segregation Principle
D - Dependency Inversion Principle

# Single Responsibility


# Open Closed 
"Software entities such as classes, modules, functions, etc. should be open for extension but closed for modification"

new functionality should be implemented by adding new classes, attributes, and methods instead of modifying existing ones

> Implementation Guidelines
- simplest implementation of Open Closed Principle is derived classes

> If OCP is not used
-  End up testing entire functionality along with the new requirement
-  QA Team need to test the entire flow
-  Costly for the org
-  Breaks the single responsibility principle
-  Harder to maintain classes

# Liskov Substitution
Objects of a superclass should be replaceable with objects of its subclasses without breaking anything

basically the subclass must be a valid object of the super clas

# Interface Segregation
Objects should only depend upon methods they're going to use

break up massive interfaces into multiple smaller interfaces


# Dependency Inversion
High-level modules should not depend on low-level modules. Both should depend on abstractions


Details should depende on the abstractions not the inverse

> The interaction between high level and low level modules should be thought of as a abstract interaction between them


Store -------> Payment Processor <---- Stripe API

Store is dependent on Stripe API for payment processing