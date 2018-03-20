# Java

Object-oriented programming language. Platform independent.

## Components

### Java Virtual Machine (JVM)

1) Converts byte code into machine readable
2) Its not platform independent

### Java Development Kit (JDK)

Development kit contains tools, executable, binaries and JVM to compile, debug and execute a java application

### Java Runtime Edition (JRE)

Runtime edition contains binaries and JVM to execute only a Java application

## Basic concepts

- Overloading: same method signature, different arguments
- Overriding: same method signature, same arguments. Parent and child classes

### Access modifier

1) public: access from anywhere
2) private: only inside the same class
3) protected: same package and subclass
4) default: only same package

### Final keyword

1) class: no other class can extend it
2) method: child class can't override
3) variable: can be assigned only once. State of the variable can change

### Static keyword

1) method: can access static variables or static methods of the class
2) variable: global, all the objects will share the same variable
3) class: only nested classes
4) static block: group of statement executed when the class is loaded into memory

### Super keyword

Access super class method when you have overridden the method in child class

### Interface

A way to achieve abstraction contract for the subclass to implement.
Class can implement multiple interfaces.

### Abstract

Class with some default method implementation for subclasses.
Abstract class cannot be instantiated.
Class can extend only one abstract class.

### Wrapper

Class representation of 8 primitives types in Java, immutable and final.

### Enum

Type whose fields consists of fixed constants, static and final.

### Annotation

Metadata about the program, no direct effect on the code.

### Reflection

Inspect and modify runtime behaviour of class, interface, enum, method or field.

### Class loader

Loads byte code program into memory when we want to access any class:
1) bootstrap: jdk classes
2) extensions: jdk extensions
3) system: classpath

### Garbage collection

Check heap memory and delete unused objects. Handled by the garbage collector

### Serialization and deserialization

Serialization: Convert object to stream (i.e. saved to file or send over the network)
Deserialization: Convert stream to objects
