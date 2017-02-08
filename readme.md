# Design Pattern Notes

## Pattern Organization

### Classifications
* Creational
* Structural
* Behavioral
* Security
* Concurrency
* Sql
* User Interface
* Relational
* Social
* Distributed

#### Creational Patterns:
* Abstract Factory
* Builder
* Factory Method
* Prototype
* Singleton
* Lazy Instantiation
* Utility Pattern

Definition:  How to instantiate objects at runtime

#### Factory Patterns Module

**Consider using when:**
* Unsure of which concrete implementation of an interface I want to return
* Creation should be separated from representation of an object
* Lots of if/else blocks when deciding which concrete class to create
* Switch statements when deciding which concrete class to create

**Intent:**
* Separate object creation (instantiation) from the decision of which object to create
* Add new classes and functionality without breaking the O in SOLID
  * Factory-produced objects
  * Factories themselves
* Store which object to create outside of the program
  * In a database
  * In a configuration file

##### Simple Factory

* Encapsulate object creation
* Allows for late-bound decisions regarding instantiation
  * configuration-based
  * other persistent storage
  * input or other dynamic data
* Caller does know what concrete factory it needs

##### Factory Method

* "Define an interface for creating an object, but let the subclasses decide which class to instantiate.  Factory Method lets a class defer instantiation to subclasses."
* Adds an interface to the factory itself from Simple Factory
* Defers object creation to multiple factories that share an interface
* Derived classes implement or override the factory method of the base




#### Structural Patterns

(placeholder)

#### Behavioral Patterns

(placeholder)

#### Security Patterns

(placeholder)

#### Concurrency Patterns

(placeholder)

#### Sql Patterns

(placeholder)

#### User Interface Patterns

(placeholder)

#### Relational Patterns

(placeholder)

#### Social Patterns

(placeholder)

#### Distributed Patterns

(placeholder)
