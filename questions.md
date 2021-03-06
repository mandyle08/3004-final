# COMP3004 Final Exam Practice Questions

## Multiple Choice (Concepts)

1. This is an example question.
    - A) choice 1
    - B) choice 2
    - C) choice 3
    - D) choice 4








## Short Answer (Concepts)

1. Describe each of the FURPS+ requirement categories and why each one is important to the requirements elicitation process.
1. Give an overview of the three models of the requirements elicitation/analysis process and list the work products encompassed by each (diagrams and tables).
1. Jack wants to save on printer ink and skip writing numbers for the functional and non-functional requirements in his document. Explain to Jack why this is probably not a smart idea.
1. A browser displays alternate text before an image finished loading. What design pattern is being employed here? Draw a small class diagram to demonstrate.
1. Karen is confused about the difference between the "Facade" and "Bridge" design patterns. Explain the difference to Karen.
1. What is the difference between a scenario and use case? During the requirements elicitation process, which of the two would you try to come up with first and why?
1. Explain the difference between the "includes" relationship and the "extends" relationship in UML use case diagrams. Are the two interchangeable? Why or why not?
1. What is primary difference between composition and shared aggregation? Would it be possible for two classes to be composed of the same object? Would it be possible for one class to be composed of two or more objects? Why or why not?
1. State machine diagrams and activity diagrams may appear similar at first glance. What is the primary difference between the two?
1. You want to modernize the old UNIX `bc` program to turn it into a GUI calculator. Assume that it would be more efficient to use the old `bc` code than to rewrite the calculator logic from scratch. What kind of design pattern might be beneficial here and why?
1. Draw a UML state machine diagram for an application that allows you to write test questions and add them to a remote test bank.
1. Suppose you have a subsystem with three classes that all share similar functionality. Unfortunately, this subsystem has very low cohesion, as none of the classes use each other's services. What transformation might you apply to your model to fix this problem?
1. What is the difference between implementation and specification inheritance? Give an example of when you might use each?
1. Why is Liskov's principle important for polymorphism as we know it?
1. Suppose you have two classes (A and B). What are the four types of possible associations between A and B and how would you map each one to source code from a UML class diagram?
1. What are the two ways of optimizing associations between classes? List the advantages and/or disadvantages of each in as much detail as possible.
1. Explain the difference between model transformation and refactoring using an example.
1. Explain the difference between reverse engineering and forward engineering using an example.
1. Consider relational databases and OO databases. List one advantage and one disadvantage of each in the context of implementing a C++ program that needs to interface with a database.
1. What is the difference between vertical and horizontal mapping in the context of mapping inheritance relationships to storage? Explain the trade-off between the two.
1. What is the difference between blackbox and whitebox testing? Why is it important to use both of them when unit testing?
1. You have a class A which is subclassed by classes A1, A2, and A3. A has virtual methods foo() and bar(). What kind of testing should you do to ensure that A1, A2, and A3 are all behaving properly?
1. Explain the process of state-based testing as it relates to a specific type of UML diagram. (Hint: What UML diagram deals with state?)
1. Name the four types of integration testing and describe each one. You may wish to support your explanation with an example.
1. Compare and contrast the waterfall and v-model life cycle models.
1. Compare and contrast the spiral and agile life cycle models.








## Long Answer / Diagrams

This section contains a few system descriptions. For each description, do the following:

1. Create a FURPS+ requirements table and elicit at least 2 requirements from each category.
1. Draw a high level use case diagram. Include several high level use cases, the system boundary box, all applicable actors.
1. Draw one or more detailed use case diagrams. Include all relevant actors and use cases, and use both includes and extends relationships.
1. Draw a state machine diagram for **ONE** use case.
1. Draw a sequence diagram for **ONE** use case.
1. Draw an activity diagram **ONE** use case.
1. Choose the best architecture for the system. Indicate which architecture you are using, and describe whether it will be an open or closed architecture.
1. Create a reasonable subsystem decomposition for the system.
1. Explain a few design patterns you could use in your system.

---

Consider the myRecipes system. The system allows users to access recipes on their own local host and access recipes on peer hosts that are part of the system. The system supports three kinds of users: cooks, chefs, and assistant chefs.

Assistant Chefs can do the following:

- browse recipes stored locally
- create new recipes locally
- edit recipes stored locally

Chefs can do the following:

- everything cooks can do
- browse recipes on other peer hosts
- download recipes from other hosts

Cooks can do the following:

- browse recipes on other peer hosts









## Short Answer (Ethics)

1. Suppose you are developing an application to help users do their taxes. In order to help generate a revenue stream, your boss demands that you include a crypto miner inside the application that can run undetected and mine bitcoin for the organization. Use the ethical decision making process to determine the best course of action.
