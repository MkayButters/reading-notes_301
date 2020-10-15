## Call Stack

- A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser)
    - When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
    - Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
    - When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
    - If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

- The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

- In Asynchronous JavaScript, we have a callback function, an event loop, and a task queue. The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.

-  The call stack maintains a record of the position of each stack frame. It knows the next function to be executed (and will remove it after execution). This is what makes code execution in JavaScript synchronous.

-  The call stack maintains a record of the position of each stack frame. It knows the next function to be executed (and will remove it after execution). This is what makes code execution in JavaScript synchronous.

#### Callstack:

1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.


## Errors

- Reference errors: This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

- Syntax errors: I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax

- Range errors: Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

- Type errors: Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible

- Tools to avoid runtime errors

    - quokka: to evaluate your code as you type
    - eslint: to make sure your style guide is consistency and it will grab you an error or two along the way and
    - TypeScript:  make JS a more strong typed experience



[<===BACK](README.MD)