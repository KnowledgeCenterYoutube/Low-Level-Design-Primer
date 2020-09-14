# Low-Level-Design-Primer
Low Level Design(LLD) or Object Oriented Design(OOD) for Coding Interviews.

## Why Low Level Design(LLD)?
Low-level Design is an important part of the software engineering interviews. Many candidates struggle in LLD interviews - owing to lack of experience and indeterminate nature of LLD interviews. These are quite open-ended in nature and lack any standard answers unlike Data Structures and Algorithms interviews. The goal of this repository is to provide fundamentals of Object-Oriented Design, and provide some case studies demonstrating how to approach low-level design interviews.


### Visit [Knowledge Center](https://www.youtube.com/c/KnowledgeCenter) for other video tutorials for Programming Interviews.

------------------------------------

# Object-Oriented Programming
Object-oriented programming(OOP) is a programming paradigm that uses Objects to design applications. In contrast, in Procedure-oriented programming programs are designed as blocks of statements to manipulate data. OOP combines data and functionality inside an entity called an "Object".

This lesson will introduce some of the basic concepts of object-oriented programming.

## Objects: 
Objects represent a real-world entity and the basic building block of OOP. 
e.g., In a Parking Lot System we will have objects such as Admin, Customer, Vehicle, Parking Attendant, System etc.
We'll look at different use-cases separately in different lessons.

## Class: 
Class is the prototype/blueprint of an Object. It is a template definition of methods and attributes of an object. 
e.g., In Parking Lot System, the Vehicle object will have attributes like Licence number, vehicle type, etc., and methods for assigning ticket, parking, etc.


## Four principles of object-oriented programming:

<img width="700" alt="java 8 and prio java 8  array review example" src="https://github.com/KnowledgeCenterYoutube/Low-Level-Design-Primer/blob/master/images/OOP_basics.png">

### Encapsulation: 
Encapsulation refers to the bundling of data with the methods that operate on that data, or the restricting of direct access to some of an object's components. It is used to hide the values or state of a structured data object inside a class, preventing unauthorized parties' direct access to them. Publicly accessible methods are generally provided in the class (getters/setters) to access the values, and other client classes call these methods to retrieve and modify the values within the object.

### Abstraction: 
Abstraction refers to hiding all but the relevant data about an object in order to reduce the complexity of the system. It can be seen as an extension of encapsulation. It is very helpful in large systems having many objects interacting with each other, because it helps in hiding internal implementation details of objects and only reveals methods which are relevant to other objects.

### Inheritance: 
In object-oriented programming, inheritance is the mechanism of deriving new classes(sub classes) from existing ones such as super class or base class and then forming them into a hierarchy of classes.

There are various types of inheritance, based on paradigm and specific language.
#### Single inheritance
where subclasses inherit the features of one superclass. A class acquires the properties of another class.

#### Multiple inheritance
where one class can have more than one superclass and inherit features from all parent classes.

#### Multilevel inheritance
where a subclass is inherited from another subclass. It is not uncommon that a class is derived from another derived class as shown in the figure "Multilevel inheritance".

### Polymorphism: 
The word polymorphism is used to describe situations where something occurs in several different forms. In object-oriented programming (OOP), it describes the concept that objects of different types can be accessed through the same interface. Each type can provide its own, independent implementation of this interface. It is one of the core concepts of OOP.
Ploymorphism can be of following types:
#### Static Polymorphism
Different methods with same name but different signatures in a class definition.
#### Dynamic Polymorphism
Base class pointer holding derived class object. Behaviour determined dynamically at run-tim.


-------------------------------------------------
### Visit [Knowledge Center](https://www.youtube.com/c/KnowledgeCenter) for other video tutorials for Programming Interviews.
-------------------------------------------------

## Object-Oriented Analysis and Design (OOAD)
Object-oriented analysis and design (OOAD) is a technical approach for analyzing and designing an application, system, or business by applying object-oriented programming, as well as using visual modeling throughout the software development process to guide stakeholder communication and product quality.

OOAD in modern software engineering is typically conducted in an iterative and incremental way. The outputs of OOAD activities are analysis models (for OOA) and design models (for OOD) respectively. 

Primary tasks in OOAD are:
* Identifying the objects in a system
* Organizing the objects by creating object model diagram
* Defining the internals of the objects(attributes)
* Defining the behavior of the objects(actions)
* Describing how the objects interact
* Implementation of methods, (internal data structures and algorithms)
* Implementation of control
* Implementation of associations
* Making a design, which can be converted to executables using OO languages.

We need a standard tool for documenting all this information. So we use UML(Unified Modeling Language). UML can be considered as the successor of OOAD. UML can represent all the concepts existing in OOAD. UML diagrams are a representation of object-oriented concepts only, understading which would be pre-requisite for learning UML.

-------------------------------------------------
### Visit [Knowledge Center](https://www.youtube.com/c/KnowledgeCenter) for other video tutorials for Programming Interviews.
-------------------------------------------------
