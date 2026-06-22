Java Object-Oriented Programming (OOP) Complete Notes

1. What is OOP?

Object-Oriented Programming (OOP) is a programming paradigm that organizes software around objects rather than functions and procedures.

- OOP models real-world entities.
- Each object contains data and behavior.
- Makes programs easier to develop and maintain.
- Java is primarily an OOP language.

Why OOP?

- Improves code organization.
- Increases code reusability.
- Enhances security.
- Simplifies maintenance.
- Makes applications scalable.

Keywords

Reusability

- Writing code once and using it multiple times.
- Reduces duplicate code.
- Achieved mainly through inheritance.

Scalability

- Ability of software to grow without major modifications.
- Easy to add new features.

Maintainability

- Easier to fix bugs and update code.

Modularity

- Dividing a program into smaller independent modules.

---

2. Class and Object

Class

A class is a blueprint or template used to create objects.

Characteristics

- User-defined data type.
- Contains attributes and methods.
- Does not occupy memory until objects are created.

Example

Student class may contain:

- Name
- Roll Number
- Age
- Display Information Method

---

Object

An object is an instance of a class.

Characteristics

- Occupies memory.
- Has state and behavior.
- Represents a real-world entity.

Keywords

State

Current value of object properties.

Behavior

Actions performed by the object.

Identity

Unique identification of an object.

---

3. Encapsulation

Encapsulation means wrapping data and methods into a single unit.

Purpose

- Protect data from unauthorized access.
- Improve security.
- Achieve data hiding.

Features

- Variables are usually private.
- Access provided through methods.

Advantages

- Better security.
- Better control over data.
- Easy maintenance.

Keywords

Data Hiding

Restricting direct access to internal data.

Getter

Method used to read data.

Setter

Method used to modify data.

---

4. Abstraction

Abstraction means showing only essential information and hiding implementation details.

Real-Life Example

ATM Machine

Visible:

- Withdraw
- Deposit
- Check Balance

Hidden:

- Internal banking processes

Benefits

- Reduces complexity.
- Improves security.
- Makes code easier to understand.

Types

Abstract Class

Can contain:

- Abstract methods
- Normal methods

Interface

Contains behavior contract that classes implement.

Keywords

Implementation

Actual logic behind functionality.

Contract

A set of rules that implementing classes must follow.

---

5. Inheritance

Inheritance allows one class to acquire properties and methods of another class.

Purpose

- Reuse existing code.
- Reduce redundancy.
- Improve maintainability.

Parent Class

Class whose properties are inherited.

Child Class

Class that inherits properties.

Types of Inheritance in Java

Single Inheritance

One child inherits one parent.

Multilevel Inheritance

Chain of inheritance.

Hierarchical Inheritance

Multiple child classes inherit one parent.

Multiple Inheritance

Not supported through classes.
Supported through interfaces.

Keywords

IS-A Relationship

Inheritance relationship.

Example:
Dog IS-A Animal

Code Redundancy

Repeating same code multiple times.

---

6. Polymorphism

Polymorphism means "Many Forms".

Same method behaves differently under different situations.

Types

Compile-Time Polymorphism

Achieved using:

- Method Overloading

Method Overloading

Same method name with different parameters.

Features

- Faster execution.
- Resolved during compilation.

---

Runtime Polymorphism

Achieved using:

- Method Overriding

Method Overriding

Child class provides its own implementation.

Features

- Resolved at runtime.
- Supports dynamic behavior.

Keywords

Dynamic Binding

Method call decided at runtime.

Static Binding

Method call decided during compilation.

---

7. Constructor

A constructor initializes objects.

Features

- Same name as class.
- No return type.
- Automatically called during object creation.

Types

Default Constructor

Provided automatically by Java.

Parameterized Constructor

Accepts parameters.

Copy Constructor

Copies values from another object.

---

8. Constructor Chaining

Calling one constructor from another constructor.

Keywords

this()

Calls another constructor of same class.

super()

Calls parent class constructor.

Advantages

- Reduces duplicate code.
- Improves reusability.

---

9. Access Specifiers

Control accessibility of members.

Public

- Accessible everywhere.

Private

- Accessible only within same class.

Protected

- Accessible within package and subclasses.

Default

- Accessible only within same package.

Importance

- Security.
- Encapsulation.
- Controlled access.

---

10. this Keyword

Refers to current object.

Uses

- Access instance variables.
- Call current class constructor.
- Pass current object.

---

11. super Keyword

Refers to parent class object.

Uses

- Access parent variables.
- Access parent methods.
- Call parent constructor.

---

12. Static Keyword

Belongs to class rather than object.

Static Variable

Shared among all objects.

Static Method

Can be called without object creation.

Advantages

- Memory efficient.
- Common data sharing.

---

13. Final Keyword

Used to restrict modification.

Final Variable

Cannot change value.

Final Method

Cannot be overridden.

Final Class

Cannot be inherited.

---

14. Abstract Class

A class declared using abstract keyword.

Features

- Cannot create objects.
- May contain abstract methods.
- May contain concrete methods.

Advantages

- Partial abstraction.
- Common functionality sharing.

---

15. Interface

Blueprint of behavior.

Features

- Supports multiple inheritance.
- Provides abstraction.
- Defines contracts.

Advantages

- Loose coupling.
- Flexibility.

---

16. Abstract Class vs Interface

Abstract Class

- Can have abstract and normal methods.
- Supports constructors.
- Partial abstraction.

Interface

- Supports multiple inheritance.
- No constructors.
- Complete abstraction concept.

---

17. Association

Relationship between two objects.

Types

Aggregation

Weak relationship.

Example:
Department has Teachers.

Teachers can exist independently.

Composition

Strong relationship.

Example:
House has Rooms.

Rooms depend on House.

---

18. Coupling

Degree of dependency between classes.

Tight Coupling

- High dependency.
- Difficult maintenance.

Loose Coupling

- Low dependency.
- Easy maintenance.

Why Loose Coupling?

- Better flexibility.
- Easy testing.
- Easy updates.

---

19. Cohesion

Measures how closely related functionalities are inside a class.

High Cohesion

- Better design.
- Easier maintenance.

Low Cohesion

- Difficult management.

---

20. Deep Copy and Shallow Copy

Shallow Copy

- References shared.
- Same memory reference.

Disadvantage

Changes affect both objects.

---

Deep Copy

- Independent memory allocation.
- Separate references.

Advantage

Changes do not affect original object.

---

21. Exception Handling

Mechanism to handle runtime errors.

Purpose

- Prevent abnormal termination.
- Maintain program flow.

Keywords

try

Contains risky code.

catch

Handles exception.

finally

Always executes.

throw

Manually creates exception.

throws

Declares possible exceptions.

---

22. Object Class

Root class of Java hierarchy.

Every class indirectly inherits Object class.

Important Methods

toString()

Returns string representation.

equals()

Compares objects.

hashCode()

Returns hash value.

clone()

Creates object copy.

---

23. Method Overloading vs Method Overriding

Overloading

- Same class.
- Different parameters.
- Compile-time polymorphism.

Overriding

- Parent-child classes.
- Same signature.
- Runtime polymorphism.

---

24. Virtual Keyword

Java does not have a virtual keyword like C++.

Why?

In Java, non-static methods are virtual by default.

Benefits

- Supports runtime polymorphism.
- Dynamic method dispatch.

---

25. JVM Related OOP Terms

Dynamic Method Dispatch

Runtime selection of overridden methods.

Runtime Polymorphism

Behavior determined during execution.

Object Creation Process

1. Memory allocation.
2. Constructor call.
3. Initialization.
4. Object ready for use.

---

Quick Revision Sheet

Four Pillars of OOP

1. Encapsulation → Data Hiding
2. Abstraction → Hide Implementation
3. Inheritance → Reusability
4. Polymorphism → Many Forms

Important Keywords

- class
- object
- this
- super
- static
- final
- abstract
- interface
- extends
- implements
- public
- private
- protected
- try
- catch
- finally
- throw
- throws

Interview Keywords

- Reusability
- Scalability
- Maintainability
- Modularity
- Data Hiding
- Dynamic Binding
- Static Binding
- Loose Coupling
- High Cohesion
- Runtime Polymorphism
- Compile-Time Polymorphism
- Constructor Chaining
- Deep Copy
- Shallow Copy

End of Notes
