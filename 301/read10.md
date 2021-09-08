# JavaScript Call Stack

## What is a ‘call’?
***A call stack is a series of program counter addresses (PCs) representing instructions from within the program. Each such address is known as a return address. The process of recording a call stack involves obtaining the return addresses from the program stack and is referred to as unwinding the stack.***

## How many ‘calls’ can happen at once?
JavaScript can do one single thing at a time because it has only one call stack.
## What does LIFO mean?
The order in which elements come off a stack gives rise to its alternative name, LIFO (last in, first out). ... This structure makes it easy to take an item off the top of the stack, while getting to an item deeper in the stack may require taking off multiple other items first.
![1](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Lifo_stack.png/350px-Lifo_stack.png)

## What causes a Stack Overflow?
A StackOverflowError is a runtime error in java. It is thrown when the amount of call stack memory allocated by JVM is exceeded. A common case of a StackOverflowError being thrown, is when call stack exceeds due to excessive deep or infinite recursion. In the above case, it can be avoided by doing programmatic changes.


# JavaScript error messages

## What is a ‘refrence error’?
***In JavaScript, a reference error is thrown when a code attempts to reference a non-existing variable.***

## What is a ‘syntax error’?
The SyntaxError object represents an error when trying to interpret syntactically invalid code. It is thrown when the JavaScript engine encounters tokens or token order that does not conform to the syntax of the language when parsing code.

## What is a ‘range error’?
Description. A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String.

## What is a ‘tyep error’?
The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type. A TypeError may be thrown when: an operand or argument passed to a function is incompatible with the type expected by that operator or function; or.

## What is a breakpoint?
At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

## What does the word ‘debugger’ do in your code?
The debugger statement stops the execution of JavaScript, and calls (if available) the debugging function. Using the debugger statement has the same function as setting a breakpoint in the code. Normally, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.
