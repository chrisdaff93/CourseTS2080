
# Interface Class
- A method() that is used by two or more classes can be made into a Interface Class
- Helps you to define methods() without exposing the info to all the use classes.


```cpp

<<interface>>
SEARCH
SearchMember(Name)
SearchGroup(Name)
SearchPage(Name)
PostSearch(Word)
```

- At a high level, an interface acts as a blueprint for designing classes
- An interface can contain only method declaration;
	- Interfaces: Implement all the methods in the class that extends the interface

- Interface support the hiding of information and protect client code.



A - - - - - - - - - - - - - - - - B **Use Interface:** A uses interface B.


## Class Diagrams Relationships Between Objects
### Abstract Class
- An abstract class is a particular type of class that cannot be instintiated
- An abstract class is designed to be inherited by subclasses that implement or override its methods
- In other words, abstract classes are either partially implemented or not implemeneted at all.
- You can have functionality in your abstract class - the methods in an abstract class can be both abstract and concrete


## Difference Between Interface Class and Abstract Class:
- Abstract: Partially or not implemented at all
- Interfaces: Need to implement all the methods in the class that extends the interface
- Abstract class: Allows you to create functionality that subclasses can implement or override
- Interface: If you want a contract on some behaviour or functionality.

## Enumerations
```cpp
<<Enumeration>>
CONNECTIONINVITATIONSTATUS
Pending
Accepted
Rejected
Cancelled
```

- Model elements in class diagrams that represent user-defined data types
- Contain sets of named indentifiers that represent the values of the enumeration


### DataTypes
```cpp
<<DataType>>
ADDRESS
streetAdress: string
city: string
state: string
zipcode: string
country: string
```

- Creating an own datatype that can store different elements all packed together
- This can be inherited to other classes and be used.
- Model elements that define data values
- You typically use data types to represent primitive types, such as integer or string types, and enumerations, such as user-defined data types.



***As computer systems grow, you have to worry more and more about controlling dependencies***
- Have does changing this class affect the rest of my diagram?

***If dependencies get out of control, each change to a system has a boad ripple effect as more and more things have to change***
- Why or why not should you update this?
- The bigger the ripple, the harder it is to change anything.


### REMEMBER!
- The trouble with class diagrams is that they are so rich, that they can be overwhelming to use
- Dont try to use all the notations available to you. Start with the simple stuff in this chapter: Classes, assossiactions, attributes, generalization, and constraints.

![[Image 14-10-2022 at 12.44.jpg]]
# ASSIGNMENT
### Same Group, Different group, or go solo!
### Recommended: Build on your use case diagram project
### Work on it next class (21st of October)
### Present - (28th of October)
- Slide wth Problem statement + Requirements + Use case diagram + Class diagram
- In addition! Each Class should have a single/two-sentence description






