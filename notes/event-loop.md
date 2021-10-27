
[event loop javascript](https://www.google.com/search?q=event+loop+javascript&gs_lcp=Cgdnd3Mtd2l6EAMYADIECAAQQzIECAAQQzICCAAyAggAMgIIADICCAAyAggAMgIIADICCAAyAggAOgcIABBHELADOgcIABCwAxBDOgYIABAWEB46CAgAEBYQChAeOgcIIRAKEKABOgcIABCHAhAUULWKAViNoAFgzacBaARwAngAgAGLAYgB7QWSAQM4LjGYAQCgAQGqAQdnd3Mtd2l6yAEKwAEB&sclient=gws-wiz)
[How JavaScript works: Event loop and the rise of Async programming + 5 ways to better coding with async/await  by Alexander Zlatkov  SessionStack Blog ](https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5)
[The JavaScript Event Loop ](https://flaviocopes.com/javascript-event-loop/)

[What is an event loop in JavaScript? ](https://www.educative.io/edpresso/what-is-an-event-loop-in-javascript)
>The event loop is the secret behind JavaScript’s asynchronous programming. JS executes all operations on a single thread, but using a few smart data structures, it gives us the illusion of multi-threading.

>The call stack is responsible for keeping track of all the operations in line to be executed. Whenever a function is finished, it is popped from the stack.

>The event queue is responsible for sending new functions to the track for processing. It follows the queue data structure to maintain the correct sequence in which all operations should be sent for execution.

>Whenever an async function is called, it is sent to a browser API. These are APIs built into the browser. Based on the command received from the call stack, the API starts its own single-threaded operation.

>we have a cyclic system for running async operations in JavaScript. The language itself is single-threaded, but the browser APIs act as separate threads.

>The event loop facilitates this process; it constantly checks whether or not the call stack is empty. If it is empty, new functions are added from the event queue. If it is not, then the current function call is processed.