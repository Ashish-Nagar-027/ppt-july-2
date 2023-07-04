# What is Execution context? how it works. 
Execution context is the concept for describing internal working of javascript code.
In JavaScript , execution context is an environment that enables the JavaScript code to get execute.
Everything in js is wrapped inside execution context .

so what really happens when we run javascript. how code gets excutes ?
answer : whenever we run javascript code an global execution context  gets created . Inside this global execution context all  javasript code gets executes in two phases
memory allocation phase   2. code execution phase
  
  Memory allocation phase is also know is memory creation phase . In this phase js will allocate memory to all the variable and functions and stores them in key value pair inside execution context. In case of variable it gives value of undefined and for functions it gives whole function as it is for value.
  In code Execution phase code js will run code line by line. Now it will place values of undefined variables 
which were created in memory allocation phase. also for every new function it js creates a new execution context 
alltogether