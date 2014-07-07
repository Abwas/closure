JavaScript Closure In Depth

**Part 1 Preparing for the journey**

**1.1 First class functions**

 **1.1.1 Assign function to a variable**

 **1.1.2 Passing function as argument to another function**

 **1.1.3 Returning function as a value from other function**

**1.2 Scoping**

 **Rule 1: Variable declaration hoisting rule**

 **Rule 2: Variable assignment hoisting rule**

 **Rule 3: Function declaration statement hoisting rule**

 **Rule 4: Function definition expression hoisting rule**

**1.3 Invocation context**

 **1.3.1 Function invocation**

 **1.3.2 Method invocation**

 **1.3.3 Constructor invocation**

 **1.3.3.1 Using prototype object**

 **1.3.4 Indirect invocation**

 **1.3.4.1 Call method**

 **1.3.4.2 Apply method**

 **1.3.4.3 Testing enumerability**

 1.3.4.4 Binding

 1.3.5 this & nested function issue


2 Understanding closures 

2.1 What is closure 

2.2 Ways to create closure



Part 2 Closure applications 

3 Deferred calls 

3.1 DOM event handlers and shared memory 

3.2 “that is this” in nested event handlers

3.3 Dealing with timers

3.4 Classical last value problem in loops

3.5 Passing arguments in callbacks

3.6 Forcing function context inside event handler

3.7 Trapping variables inside AJAX callbacks

3.8 Using closures with Node.js events

3.9 Canvas RequestAnimationFrame API and closure


4 Maintaining privacy 

4.1 Create private variables using closure

4.2 Privileged method knows the secret 

4.3 Implementing block scope

4.4 Namespaces


5 OOP optimizations 

5.1 Extend lifetime of the constructor 

5.2 Avoid too much closure

5.3 Function constructor and closure rule 


6 Design patterns and closure 

6.1 Implement publisher subscriber pattern

 6.1.1 Groundwork

 6.1.2 Adding subscription code

 6.1.3 Classical loop problem

 6.1.4 Exceptions and async event handlers 

6.2 Module pattern

6.3 Factory pattern 


7 Currying and Memoization

7.1 Partial application and closures

 7.1.1 Default ES5 left partial application

 7.1.2 Making right partial application

 7.1.3 Generic currying 

7.2 Memoization 

8 Utilities

 8.1 monkey patching

9 Memory sharing patterns

9.1 Common memory

9.2 Independent scope chain
