<h1 style="text-align: center; color: aliceblue; font-family: 'Segoe UI Semilight', sans-serif; font-weight: bold; font-size:  12pt ">
CMP4300 | Introduction to Game Programming in C++ 
</h1>
<h6 style="text-align: center; color: aliceblue; font-family: 'Segoe UI Semilight', sans-serif; font-weight: bold; font-size:  12pt ">
Santiago Arellano  
</h6>

***
<p style="font-family: 'Segoe UI Semilight', sans-serif; color: bisque">

Introduction to game programming is a course that teaches the fundamentals of game implementation, rather than design,
meaning that in most cases we will worry more about how the game is running, coded and the methodologies (like programming paradigms and 
design patterns) rather than how the game is designed from the ground up in non technical terms, like art design, level design, etc.

This course follows the idea of presenting three main concepts

    - Game Engine / Gameplay Programming
    - C++ / SFML (Graphics Library)
    - Programming that makes video games possible

We will be making our own game engine throughout this course.
</p>

***
<p>
Inside the course we will be looking at a series of data points, more like skills, that we must adquire in order to perform
when it comes to building and managing our own code in terms of the game engine, and generally regarding our programming structure 
for this course, these are:

    - Pointers / References (CMP2102)
    - Structs / Classes / Inheritance (CMP2102)
    - Operator Overloading (CMP2102)
    - Stack / Heap Memory (CMP2102)
    - STL Containers / Algorithsm / Streams (CMP2101-2)
    - Smart Pointers
    - RAII (Resource allocation is initialization) 
    - Factory Design Pattern
    - SFML / ImGui Library

The following course has a set of goals defined for the rest of the given lectures, we will learn the following concepts,

    - Game Programming from Scratch
    - ECS (Entity-Component-Systems) paradigm,
    - Game Programming patterns
    - Software design principles
    - Implementations of games using these concepts 

</p>

***
<p>
In the present course we will be working in the creation of our own game engine, while there are others (Unity, Unreal, Godot...), but what we want is to 
create an engine that will allow us to program games easily, not with a full UI interface, that can be done later, etc.
But this engine will have the following properties

    - ECS programming architecture in C++ (not the only one)
    - Ability to program many 2D games 
    - Incorporating game scenes,
    - Own level editor for projects
</p>

***

<p>
In the course we will use a bunch of mathematics, we need to know how to represent vectors, shaders, shadows, lightning, velocity, etc.

We will also learn about game config, dialogues, triggers, weapons, loading and saving, Ai for the game.

As we know ECS is Entities, Components, Systems,

    - Entity: Any object in the game, players, platforms, tiles, bullets enemies, etc.
        -  Entities can be thought of as holders for components.
ECS is a software design paradigm, for all software and not just games,

Since classes grow exponentially through the use of OOP and OOD in game design, we can use ECS since it uses a more appropriate method,
For instance, 

    - An entity can be anything, literaly anyting in game, and through the use of components (properties that can aatach to Entities), we develop a horizontal structture 
    and through these components we create a linear structure where our properties (components( are attached linearly and give our entities different abilities, without defining n levels of
    inheritance.

Hence, ECS uses <code> Composition-Based design</code>. Now we have somethign that looks like this

```plantuml
Entity -> Any object in the game,
Component -> Properties attached to entities, they are raw data,
Systems -> Methods used to communicate these properties.
```

Note: We are defining ECS for our game definition, what we use and how we use it, but to implement the game we will use OOP
using classes and a little bit of inheritance. 
</p>