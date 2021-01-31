# Function

## What is Function ?
_A function is a group of reusable code which can be called anywhere in your program. This eliminates the need of writing the same code again and again. It helps programmers in writing modular codes. Functions allow a programmer to divide a big program into a number of small and manageable functions._

## function Definition
_Before we use a function, **we need to define it**._
_The most common way to define a function in JavaScript is by using the function keyword, followed by a unique function name, a list of parameters (that might be empty), and a statement block surrounded by curly braces._

* Syntax
* The basic syntax is shown here.

     > function functionname(parameter-list) {
        >   statements
        >  }

* Calling a Function
_To invoke a function somewhere later in the script, you would simply need to write the name of that function as shown in the following code._

>var setName;
>function getUser() {

 >   setName = prompt("Enter Your Name ?");
>  console.log(setName);

>}
>getUser();

