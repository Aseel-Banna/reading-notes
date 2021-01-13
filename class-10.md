# Error Handling & Debugging
- To find the source of an error, it helps to know how scripts are processed. 
- There are some tasks cannot complete until another statement or function has been run.
- The JavaScript interpreter uses the concept of execution contexts. 
- EXECUTION CONTEXT:
  - GLOBAL CONTEXT: Code that is in the script, but not in a function. 
  - FUNCTION CONTEXT: Code that is being run within a function.
  - EVAL CONTEXT (NOT SHOWN): Text is executed like code in an internal function called eval{).
- VARIABLE SCOPE:
  - GLOBAL SCOPE: If a variable is declared outside a function, it can be used anywhere because it has global scope. 
  - FUNCTION-LEVEL SCOPE: When a variable is declared within a function, it can only be used within that function.
- The JavaScript Interpreter one line of code at a time.
- Each time a script enters a new execution context, there are two phases of activity: 
  - PREPARE:
     - The new scope is created.
     - Variables, functions, and arguments are created.
     - The value of the this keyword is determined.
     - Call functions before they have been declared.
     - Assign a value to a variable that has not yet been declared.
  - EXECUTE:
     - Now it can assign values to variables.
     - Reference functions and run their code.
     - Execute statements.
- In the interpreter, each execution context has its own va ri ables object, which holds the variables, functions, and parameters available within it and each execution context can also access its parent's variables object. 
- If a JavaScript statement generates an error, then it throws an exception.
- If you are anticipating that something in your code may cause an error, you can use a set of statements
to handle the error.
- Error objects can help you find where your mistakes are and browsers have tools to help you read them.
  - Property:
     - name 
     - message 
     - fileNumber 
     - lineNumber
  - OBJECT:
     - Error
     - Syntax Error
     - ReferenceError
     - TypeError
     - Range Error
     - URI Error
     - EvalError
- There are two things you can do with the errors:
  1. DEBUG THE SCRIPT TO FIX ERRORS.
  2. HANDLE ERRORS GRACEFULLY.
- Debugging is about deduction: eliminating potential causes of an error. 
- To solve the error you can:
  1. Look at the error message.
  2. Check how far the script is running.
  3. Use breakpoints where things are going wrong.
- The console will show you when there is an error in your JavaScript. 
- You can pause the execution of a script on any line using breakpoints.  
- If you know your code might fail, use try, catch, and finally. 
- If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them. 

