Anatomy of a class.

	Source file -> Class File -> Methods -> Statemtents

- Source Code:  *Hold one class definition*.
- Class Code: *Has one or more methods*.
- Methods Code: *Has every instructions for do a function*.

# Anatomy of the ***Source File***

![[Pasted image 20231227183405.png]]
[[Head_First_Java_Second_Edition.pdf#page=42]]
___

# Object Orientend ***Programming*** (*OOP*)

	When you design a class, think about the objects that will be created from that class type. Think about:

* Things the object **knows**
* Things the object **does**

Things an object *knows* about **itself** are called -> ***intance variables***
Things an object *do* are called -> ***methods***

Things an object *knows* about itself called **instance variables**. They represent an object's state (the data), and can have unique values for each object of that type.

![[Pasted image 20231229154252.png]]
[[Head_First_Java_Second_Edition.pdf#page=68]]

___
# Variables
	Java cares about type.
* Variables must have a **type**
* Variables must have a **name**

```java
int count;
```
## We have two types of variables...
- Primitive: hold fundamentals values (think: simple bit patterns) including integers, booleans, and floating point numbers.
	
- Object Reference: hold *references to objects*.
	- The 3 steps of object declaration, creation and assigment:
		1. Declare a reference variable: **Dog myDog** =  new Dog();
		2. Create an object: Dog myDog = **new Dog();**
		3. Link the object and the reference: Dog myDog **=** new Dog();
	
Variable is just a cup. A container -> It *holds* something.

___

# How Objects Behave

	A class is the **blueprint** for an *object*. When you write a *class*, you're describing how the JVM *should make an object* of that **type**. 

Intance variables (state) -> **knows**
Methods (behavior) -> **does**

A method **uses** parameters. A caller **passes** arguments.

# The three things we'll write for each class
	prep code | test code | real code

- Prep code: A form of pseudocode, to help you focus on the lofic without stressing about syntax.
- Test code: A class or methods that will test the real code and validate that it's doing the right thing.
- Real code: The actual implementation of the class. this is where we write real *Java* code.

> This concepts are practices of **Extreme Programming** (XP)

# Extreme Programming -> *XP*

	Make small, but frequent, releases.

- Don't put in anithing that's not in the spec (no matter how tempted you are to put in functionality "for the futurue").

- Write the *test* code first.

- No killer schedules; work **regular** hours.

- Refactor (improve te code) whenever and wherever you notice the **opportunity**.

- Don't release anithing until it passes all the test.

- Set realistic schedules, based around **small** releases.

- Keep it **simple**.

- Program in pairs, and move people around so that everybody knows pretty much everything about the code

# Java Library

