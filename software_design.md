# Software Design Lab

---

## Question 1: What do we mean by coupling and cohesion when discussing structured design?
Coupling refers to the dependance of one module on another module. High coupling refers to tight coupling and an example of it is inheritance. Low coupling refers to loose coupling and an example of it is interfaces. Coupling essentially is the idea of whether changes to one module may affect another module. Dependency inversion reduces coupling.
Cohesion refers to the degree how closely related functions are in working towards a single purpose within a module. High cohesion means they work closely together towards a single goal, whereas low cohesion means that the functions are loosely related and can work towards multiple goals. Single responsibility can be related to high cohesion.

## Question 2: What is the difference between top-down and bottom-up design? Which best describes a function oriented design?
Top-down refers to taking a big problem and breaking it into smaller problems until you have problems which are much easier to solve. Examples of this is function oriented programming.
Bottom-up refers to using smaller parts of the system and combining them to complete full system. Examples of this is object oriented programming.

## Question 3: In which design methodology would a class diagram be most useful?
In the bottom-up approach as class diagrams help understand how to use smaller components to build up into larger goals.

## Question 4: What are the four pillars of object oriented programming? Give a single-sentence description of each.
Abstraction: Hide away implementation details of how something is done. (Think interfaces and abstract classes)
Encapsulation: Refers to hiding away data and code details and only exposing what is needed. You dont need access to certain private attributes in a class, as long as the method can utilise them to carry out a function. Those details are unnecessary for user.
Inheritance: A child class inherits the attributes and characteristics of a parent class.
Polymorphism: Refers to overriding and overloading of methods to achieve different functionality.

## Question 5: What is the strategy pattern? How would its implementation differ between a functional and object oriented system?
A strategy pattern uses different strategies (cases) which can be selected by the delegator. In functional, functions would be used to create strategies, where as in object oriented, interfaces, abstractions and classes would be used to implement strategies.

## Question 6: Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
