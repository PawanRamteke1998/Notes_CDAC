# Date : 16-04-2023

# Day 1 :

Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam
Systam

## Topics:

- Introduction to Datastructure
- Computational Thinking
- Types of Data Structures
- Recursion

### Basics

- Data : collection of raw facts.
- Data structure: organization of data needed to solve the problem.
- Algorithm: Outline, the essence of the computational process.It is a step by step instructions.
- Program: -An implementation of the algorithm in some programming language.

## Algorithm:

- It is a sequence of unambiguous instructions/operations for solving a problem,for obtained the required output for any legitimate input in a finite amount of time.

### Characteristics of algorithms

- Input:some input value is required.
- Output:atleast one output.
- Unambiguity:instructions must very clear and simple.
- Finiteness:limited amount of instruction.
- Effectiveness:instructions in program must be clear and it affects the overall program.
- Laguage independent:output for different programming language must be same.

### Good Algorithm:

    Efficiency:
    	- 1. Running time
    	- 2. Space used by the program

    Note: The number of bits in an input  will define the efficiency of the algorithm.

### Algorithm Design Strategies:

    1.Brute force
    2.Divide and Conquer
    3.Decresea and conquer
    4.Transform and conquer
    5.Greedy approach
    6.Dynamic programming
    7.Backtracking
    8.Branch and bound
    ...etc

### Analysis of Algorithm

    - Correctness
      -Time efficiency
      -Space efficiency
    - An algorithm is said to be efficient and fast, it takes less time to execute
    and consume less memory space

    - The performance of algorithm can be measured by the properties:
    	1. Time complexity
    	2. Space complexity

# Data structure:

    - It is an organization, management and storage of data.
    - It will enable the efficient access and modification.


## Types of Data structure:

    1. Linear Data Structure
    	-Elements can be arranged in 1 dimension, are known as linear data strucuter.
    	- eg., array, queue, stack, linked list,...

    2. Non-Linear Data Structure
    	- Elements can be arranged in one to many, many to one and many to many dimension.
    	- e.g., tree, graph, table, ...

## Differntiate between Linear and nonlinear data structure.

### Linear Data Structures:

- Linear data structures are data structures where the elements are arranged in a sequential manner, with each element connected to its predecessor and successor.
- Examples of linear data structures include arrays, linked lists, stacks, and queues.
- In a linear data structure, the data is accessed in a linear manner, which means that each element is processed one after the other.

### Nonlinear Data Structures:

- Nonlinear data structures are data structures where the elements are not arranged in a sequential manner, and there is no one-to-one relationship between the elements.
- Examples of nonlinear data structures include trees, graphs, and heaps.
- In a nonlinear data structure, the data is accessed in a non-linear manner, which means that each element may be processed in a different order, depending on its relationship with other elements in the structure.

- The key difference between linear and nonlinear data structures is the way they store and organize the data.
- In linear data structures, the data is stored in a sequential manner, while in nonlinear data structures, the data is stored in a non-sequential manner.
- Linear data structures are easy to implement and manage, but they have limited flexibility, whereas nonlinear data structures are more complex and harder to manage, but they offer greater flexibility and can be used to represent more complex relationships between the data elements.

## Differntiate between Primitive and non primitive data structure.

- Primitive Data Structure
  - Primitive data structures are basic data types that are built-in to a programming language and can directly store a single value.
  - They are simple and cannot be broken down into smaller components.
  - Examples of primitive data structures include integers, floating-point numbers, characters, and Boolean values.
  - Linear data structures have elements that are arranged in a linear or sequential manner, and examples of linear data structures include arrays, linked lists, and stacks.
- Non-Primitive Data Structure
  - Non-primitive data structures, on the other hand, are more complex and can store multiple values or a collection of values. They are usually created by the programmer and are not built-in to the programming language. Non-primitive data structures can be further classified into linear data structures and non-linear data structures.
  - Non-linear data structures have elements that are not arranged sequentially, and examples of non-linear data structures include trees, graphs, and hash tables.
- In summary, the main difference between primitive and non-primitive data structures is that primitive data structures are simple and built-in to a programming language, while non-primitive data structures are more complex, created by the programmer, and can store multiple values or collections of values.

### Keyword:

    - Linear
    - Non-linear
    - homogeneous
    - non-homogeneous
    - static
    - dynamic

### Advantage:

    - efficiency
    - resuability
    - abstraction (ADT: Abstract data type)

### Abstract Data type:

- ADT is a type or class for objects whose behaviour is defrined by a set of value and set of operations.
- "abstract" because it gives an implementation independent view.

# Recursion:

    -Any function which call itself directly or indirectly is called Recursion.
    -important : recursive function get terminate.
    -eg: tower of hanoi (TOH), tree traversals, DFS and BFS, sorting algos,....

## Direct recursion:

```java
    void f1()
    {
      f1()// recursive call
    }
```

## Indirect recursion:

```java
    void f1()
    {
      f2()// recursive call
    }
    void f2()
    {
      f1()// recursive call
    }
```

    - Code compact  but complex to understand.
    - Code is smaller in size, easier to write recursive code.
    - termination of code: base condition is to be reached.
    - requires extra space on the stack.

### Home work

    1.Tower of Hanoi
    2.Factorial
    3.Fibnocci series (n=5,10,25,50,100)
    4.Greatest common divisor
    5.Printing all permutations of the given string.
