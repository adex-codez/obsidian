The following are the core concepts in functional Programming that shapes how to write fully functional programs: 

## Pure Functions

Pure functions are functions that when giving the same input return the same output. I.e. a function that receives one  and sends back two  and when giving the same input which is one returns the same output which is two.

## Side Effects

A pure function is a said to be a function with no side-effects which means that the function does not interfere(through a state mutation) with any other components of our application. Functional Programming embraces the fact that our code do not contain side-effects that interfere with other parts of programs.

## Stateless vs Stateful

functional programming embraces stateless code which is code that does is not influenced by previous events.
Stateful code  is very difficult to test and becomes a problem when we are trying to implement resilient and scalable system.


## Declarative vs Imperative

FP often uses declarative programming as one of its main benefit.
Imperative programming: It focuses on  describing how a program operates. It is a programming paradigm that uses statement that changes the state of the program. an imperative program consists of commands for the computer to perform.

Declarative programming: This is a programming paradigm that expresses the logic of a computation without describing its control flow. It describes what the program must accomplish in terms  of the problem domain, rather than describing how to accomplish it as a sequence of steps.

## Immutability

FP encourages immutability which is the concept that enforces that when a  value is assigned to a  variable it cannot be changed. 

## Function as first class citizens 

When we say functions as first class we mean that function can be saved as variable and a function can be passed as an argument of another function which also means that functions can do anything that a variable can do.

## Lambda Expressions

This are expressions that can be used to declare an anonymous functions (functions that do not have a name)

## Function Arity

The arity of a function is the number of arguments a function takes.  A unary function is a function that takes one argument.
Unary functions are very important to functional programming because they facilitate the utilization of the function composition pattern.

## Higher Order Functions

Higher other functions are function that takes one or more function as an argument and returns a function as a result

## Laziness 

Many functional programming languages feature lazy-evaluated APIs. The idea behind lazy-evaluations is that operations are not computed until doing so cannot be postponed.







