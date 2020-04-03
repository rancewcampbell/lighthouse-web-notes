# Day 4

## Callbacks

* Functions are 'first-class objects' which means 2 things: 
  1. Functions can be stored in variables and passed around
  2. Functions can do everything other objects can do (like having properties)

* Enter callback functions:
  1. A callback is a function passed into another function (called the 'receiver')
  2. The 'receiver' function is tehrefore accepting behavior to perform by calling the callback function that it now has access to
  3. The 'receiver' function can decide to call the callback function at any time, as mnay time as it wants

* Do not invoke the function when passing it in, the method using the function will do that for me.

* Functions that take in callbacks are referred to as Higher Order Functions

* A Higher-Order function is a function that operates on other functions

## Lecture Notes 

* There is a key difference between an arrow function and a regular function declaration: how both react to the `this` keyword.

* "Always use `const`" so that when you need to use let you will get an error.

## VIM

* Vim has two modes: edit and command
  * Edit mode is where you can physically edit document
  * Command mode allows navigation through the document. This is the default mode.

## Closures

* When a function retains the context of a parent function, it is called a 'closure'.