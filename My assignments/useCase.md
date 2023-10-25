# Use Case 
* high-level method of describing the functionality of a system in a simple way that can be understood by all users.
* They help express user requirements and show how users will perform tasks on the system from their point of view.
* the process of modeling a system's functions in terms of business events and how users will perform tasks on the system.
# Elements
1) System: Represented by a rectangle shape, it could be a web application, software component, or business process.
2) Actors: Represented by stick figures, actors could be any user that has access to the system. They can be human, organizational, or external devices, or even represent time.
3) Use Cases: Represented by ovals, use cases are descriptions of functions that will be performed by actors on the system.
4) Relationships: Represented by different types of lines, relationships describe how actors and use cases are connected.

# Types of Actors
1) Primary System Actors: Actors that directly interface with the system.
2) Primary Business Actors: Actors that benefit from the execution of the use case.
3) External Server Actors: Stakeholders that respond to requests from the use case.
4) External Receiver Actors: Stakeholders who are not primary actors but receive something of value from the use case

# Types of Relationships
1) **Associations**: Represent the relationship between an actor and a use case where an interaction occurs between them.
* Associations are represented by a **solid line** and can be **bidirectional** or **unidirectional**.
2) **Include**: Represents that one use case includes another use case.
* It is represented by an **arrowhead line** pointing from the including use case to the included use case.
3) **Extend**: Represents that one use case extends another use case by adding additional functionality.
* It is represented by an **arrowhead line** pointing from the extended use case to the extending use case.
4) **Abstract** Use Case: Represents two or more use cases that perform steps of identical functionality.
5) **Depends On**: Represents that a use case must be performed before the current use case.
* It is represented by an **arrowhead line** starting from the use case that depends on the other use case.
6) **Inheritance**: Represents that two actors initiating the same use case can be inferred and assigned to a new abstract actor to reduce redundancy.
7) **Generalization**: Generalization is used to show that one actor or use case inherits the characteristics of another actor or use case. It is denoted by an arrowhead line with an open triangle pointing to the generalized actor or use case.
