# Hello_Haskell
This repo contains the notes and scripts that from reading the book [Get Programming with Haskell](https://www.manning.com/books/get-programming-with-haskell). 

Notes:

## Chapter 2 notes
* Functional programming has a reputation for being a challenging topic to master. 
* All functions in Haskell start with a lowercase letter. 
* 3 laws for functions in Haskell  
    * All functions must take an argument. 
    * All functions must return a value
    * Anytime a function is called with the same argument, it must return the same value. **referential transparency**
* Lambda calculus allows for a universal model of computation. 
* Aim of functional programming: to bring the power of mathematics to the programmer in a usable way. 
* Haskell is a safe programming language. A safe programming language is one that forces your programs to behave as expected. 
* Nice example on page 17
* Haskell doesn't allow functions to have side effects, which explains why all Haskell functions must take an argument and return a value. 
* The only catch with variables in Haskell is that they're not really variable at all. 
* When working in GHCi, you're allowed to reassign variables. 

## Chapter 1 notes
* Think before you hack. Haskell strongly rewards taking time and thinking through problems before running problems. 
* The main benefit of a compiler over an interpreter is that because the compiler transforms code in advance, it can perform analysis and optimization fo the code you've written. 
* A computer built with von Neumann architecture isn't the only way to perform computation. Haskell is one different method of programming that often solves problems simply by describing them. 