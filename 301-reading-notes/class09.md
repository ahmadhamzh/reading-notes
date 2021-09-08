# Understanding the JavaScript Call Stack

###  What is a ‘call’?

* The call stack is primarily used for function invocation (call)

### How many ‘calls’ can happen at once?

* he call stack is single, function(s) execution, is done, one at a time, from top to bottom.

### What does LIFO mean?

* (Last In, First Out), it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

### an example of a call stack and the functions that would need to be invoked to generate that call stack

    function firstFunction(){
      throw new Error('Stack Trace Error');
    }

    function secondFunction(){
      firstFunction();
    }
    
    function thirdFunction(){
      secondFunction();
    }
    
    thirdFunction();

![Stack trace error](https://cdn-media-1.freecodecamp.org/images/zOINLHPC8E56ac8yyINYOFWeImsjM2Wk2rdU)
Stack trace error

* You will notice that the arrangement of the functions as a stack begins with the firstFunction() (which is the last function that got into the stack, and is popped out to throw the error), followed by the secondFunction(), and then the thirdFunction() (which is the first function that gets pushed into the stack when the code is executed).

### What causes a stack overflow?

* A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


### **In summary**

The key takeaways from the call stack are:

1. It is single-threaded. Meaning it can only do one thing at a time.

2. Code execution is synchronous.

3. A function invocation creates a stack frame that occupies a temporary memory.

4. It works as a LIFO — Last In, First Out data structure.


---
# JavaScript error messages

### What is a ‘refrence error’?

* This is as simple as when you try to use a variable that is not yet declared you get this type of errors.

### What is a ‘syntax error’?

* this occurs when you have something that cannot be parsed in terms of syntax,

### What is a ‘range error’?

* Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

### What is a ‘tyep error’?

*this how up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

### What is a breakpoint?

* breakpoint give you the ability to see what has happened before that point and you can try and evaluate the next lines to check if everything is outputting what you are expecting.

### What does the word ‘debugger’ do in your code?
 
  * it's breakpoint you use it to handele error and know what happened before that boint .

### Conclusion
  * Being able to read error messages and practising debugging is one of your biggest weapons has a developer, do it frequently and with enough time you will notice a great decrease in the time you spend on each error that you find along the way. And remember, before a commit/push, remove all the debugging stuff from your code.

  ---

  ### refrences

  * [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/) 

  * [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

  * [ist of errors](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
