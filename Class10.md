# **In memory storage**

# **JavaScript Call Stack**


## **What is a ‘call’?**
### a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).


## **What does LIFO mean?**

![img](https://image.shutterstock.com/image-photo/last-first-out-lifo-accounting-260nw-425567215.jpg)

### Last In, First Out (LIFO) principle : When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## **Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**

![img](https://cs.gmu.edu/~kauffman/cs222/figs/side-by-side.png)




## **What causes a Stack Overflow?**

### A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


# **-JavaScript error messages**


## **What is a ‘refrence error’?**

![](https://res.cloudinary.com/practicaldev/image/fetch/s--UWXFwZtZ--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://codewithwolf.com/assets/img/reference-error-type-error-console.png)

### This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

**console.log(foo) // Uncaught ReferenceError: foo is not defined**

## **What is a ‘syntax error’?**

**JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1**

## **What is a ‘range error’?**


 ### this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.




### Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

**var foo= []**
**foo.length = foo.length -1 // Uncaught RangeError: Invalid array length**


## **What is a ‘tyep error’?**

## The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type. A TypeError may be thrown when: an operand or argument passed to a function is incompatible with the type expected by that operator or function. 

## **What is a breakpoint?**
## will make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values. The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.


## **What does the word ‘debugger’ do in your code?**

## that allows you to step through another program one line at a time. This is very useful when trying to identify incorrect code and analyze how a program "flows". Key concepts include: Breakpoints, Stepping, and Viewing data.



## References:

* [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

* [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

