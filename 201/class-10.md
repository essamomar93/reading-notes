## EXECUTION CONTEXT & HOISTING: 
Each time a script enters a new execution context, there are two phases of activity:  
1. PREPARE : 
* The new scope is created  
* Variables, functions, and arguments are created 
* The value of the this keyword is determined 
2. EXECUTE: 
* Now it can assign values to variables 
* Reference functions and run their code 
* Execute statements

 ### If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code.  

 ERROR OBJECTS :
 * Error: Generic error - the other errors are all based upon this error .
 * Syntax Error: Syntax has not been followed 
 * Ref erenceError: Tried to reference a variable that is not declared/within scope .
 * TypeError: An unexpected data type that cannot be coerced .
 * Range Error : Numbers not in acceptable range .
 * URI Error: encodeURI ().decodeURI(),and similar methods used incorrectly .
 * Eval Error : eva l () function used incorrectly. 

 ### HOW TO DEAL WITH ERRORS ? 
 1. DEBUG THE SCRIPT TO FIX ERRORS :  
If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. 

2. HANDLE ERRORS GRACEFULLY :  
You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements.   


