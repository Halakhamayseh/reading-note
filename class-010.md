# Error Handling & debugging 

> JavaScript can be hard to learn and everyone makes mistakes when writing it.

- ORDER OF EXECUTION 
> The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:

- EXECUTION CONTEXTS 
> the JavaScript interpreter uses the concept of execution contexts

- EXECUTION CONTEXT & HOISTING 
> Each time a script enters a new execution context, there are two phases
of activity: 
 
 >> 1. PREPARE 
 >>> - The new scope is created
 >>> - Variables, functions, and arguments are created
 >>> - The value of the this keyword is determined

 >> 2. EXECUTE
 >>> - Now it can assign values to variables
 >>> -  Reference functions and run their code
 >>> - Execute statements

 - UNDERSTANDING 
 > each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. 
 > If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception handling code. 

 - ERROR OBJECTS 
> Error objects can help you find where your mistakes are and browsers have tools to help you read them.
>> ERROR OBJECTS CONTINUED
>>> **Syntax Error** *SYNTAX IS NOT CORRECT*,**Reference Error** *VARIABLE DOES NOT EXIST*

- HOW TO DEAL WITH ERRORS 
> Now that you know what an error is and how the browser treats them, there are two things you can do with the errors. 

1.  DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY 

- A DEBUGGING WORKFLOW
> Debugging is about deduction: eliminating potential causes of an error. 
>> *WHERE IS THE PROBLEM?*, *WHAT EXACTLY IS THE PROBLEM?*

- BROWSER DEV TOOLS & JAVASCRIPT CONSOLE 
> console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.

- TRY, CATCH, FINALLY
> This example displays JSON data to the user
>> `if (response) {`
`try{`
`var deal data = JSON . parse(response)`;
`showContent (dealData);`
`}catch(e) {`
`var errorMessage = e.name + ' ' + e .message;`
`console . log(errorMessage);`
`feed.innerHTML = '<em>Sorry, could not load</em>`
`finally {`
`var l i nk= document . create Element('a'); `
`link. innerHTML = ' <a href="tr y-catch-finally.html">rel oad<la>';`
`feed.appendChi l d{link); `
`}}`

- THROW ERROR FOR NaN
> **If you try to use a string in a mathematical operation (other than in addition), you do not get an error, you get a special value called NaN (not a number).**

- DEBUGGING TIPS 
> **Here are a selection of practical tips that you can try to use when debugging your scripts**

- COMMON ERRORS 
1. MISSED/ EXTRA CHARACTERS
2. DATA TYPE ISSUES 
