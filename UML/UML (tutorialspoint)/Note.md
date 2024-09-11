# Note

## Overview

- UML stands for Unified Modeling Language
- Object Management Group (OMG)

### A Conceptual Model of UML

- A conceptual model can be defined as a model which is made of concepts and their relationships.
- A conceptual model is the first step before drawing a UML diagram. It helps to understand the entities in the real world and how they interact with each other.

**The conceptual model of UML can be mastered by learning the following three major elements.**

- UML building blocks
- Rules to connect the building blocks
- Common mechanisms of UML

#### Object-Oriented Concepts

UML can be described as the successor of object-oriented (OO) analysis and design.  
Objects =  (data+methods).  
Data = state of object.  
Class describes -> objects.  
Class are alse form a hierarchy to model of real world stsytem.
hierarchy -> represent inheritance
They are also have onther association.  

Objects are the real-world entities that exist around us and the basic concepts such as abstraction, encapsulation, inheritance, and polymorphism all can be represented using UML.  

fundamental concepts of the object-oriented world : `Objects`, `Class`, `Abstraction`, `Encapsulation`, `Inheritance` and `Polymorphism`.

##### OO Analysis and Design

**Design** means collaboration of identified objects.  
The most important purpose of **OO analysis** is to identify objects of a system to be designed.  

**The purpose of OO analysis and design** can described as

- Identifying the objects of a system.
- Identifying their relationships.
- Making a design, which can be converted to executables using OO languages.

`OO Analysis → OO Design → OO implementation using OO languages`  

The above three points can be described in detail as  

- During OO analysis, the most important purpose is to `identify objects and describe them` in a proper way. If these objects are identified efficiently, then the next job of design is easy. The objects should be `identified with responsibilities`. `Responsibilities are the functions performed by the object`. Each and every object has some type of responsibilities to be performed. When these responsibilities are collaborated, the purpose of the system is fulfilled.
- The second phase is OO design. During this phase, emphasis is placed on the requirements and their fulfilment. In this stage, `the objects are collaborated according to their intended association`. After the association is complete, the design is also complete.
- The third phase is OO implementation. In this phase, the design is implemented using OO languages such as Java, C++, etc.

##### Role of UML in OO Design

used to model software and non-software systems.  

## UML - Building Blocks

UML can be mastered by learning the following three major elements:  

UML building blocks  
Rules to connect the building blocks  
Common mechanisms of UML  

The building blocks of UML can be defined as:

- Things
- Relationships
- Diagrams

### Things

- Structural
- Behavioral
- Grouping
- Annotational

#### Structural Things

Structural things define the `static` part of the model. They represent the physical and conceptual elements.  
`Class` − Class **represents** a set of **objects** having similar responsibilities.    
`Interface` − Interface **defines** a set of **operations**, which specify the responsibility of a class.  
`Use case` − Use case **represents** a set of **actions** performed by a system for a specific goal.  
`Component` − Component **describes** the **physical part** of a system  
`Node` − A node can be **defined** as a **physical element** that exists at run time.  

#### Behavioral

A behavioral thing consists of the `dynamic` parts of UML models  
`Interaction` − Interaction is **defined** as a **behavior** that consists of a group of messages exchanged among elements to accomplish a specific task.
`State machine` − State machine is useful when the state of an object in its life cycle is important. It **defines** the **sequence of states an object** goes through in response to events. Events are external factors responsible for state change

#### Grouping Things

Grouping things can be `defined as a mechanism to group elements` of a UML model together.  
`Package` − Package is the only one grouping thing available for **gathering** **structural and behavioral things**.  

#### Annotational Things

Annotational things can be defined as a mechanism `to capture remarks, descriptions, and comments` of UML model elements.  
`Note` - A note is used **to render comments, constraints, etc.** of an UML element.  

### Relationships

It shows how the elements are associated with each other and this association describes the functionality of an application.  
`Dependency` is a relationship between two things in which change in one element also affects the other.  
`Association` is basically a set of links that connects the elements of a UML model. It also describes how many objects are taking part in that relationship.  
`Generalization` can be defined as a relationship which connects a specialized element with a generalized element. It basically describes the inheritance relationship in the world of objects.  
`Realization` can be defined as a relationship in which two elements are connected. One element describes some responsibility, which is not implemented and the other one implements them. This relationship exists in case of interfaces.  

### UML Diagrams

UML diagrams are the ultimate output of the entire discussion. All the elements, relationships are used to make a complete UML diagram and the diagram represents a system.  

## UML - Architecture


