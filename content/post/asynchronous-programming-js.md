---
title: "Asynchronous Programming Js"
date: 2020-12-15T09:21:32-08:00
draft: false
---

Promises and observables are all about: handling asynchronous execution. There are different ways in JavaScript to create asynchronous code.

- Callbacks
- Promises
- Async/Await
- RxJS Observables

Callbacks
This is the old-fashioned classical approach to asynchronous programming. You provide a function as an argument to another function that executes an asynchronous task. When the asynchronous task completes, the executing function calls your callback function.
The main disadvantage of this approach occurs when you have multiple chained asynchronous tasks, which requires you to define callback functions within callback functions within callback functions… This is called callback hell.
Promises
Promises have been introduced in ES6 (2015) to allow for more readable asynchronous code than is possible with callbacks.
The main difference between callbacks and promises is that with callbacks you tell the executing function what to do when the asynchronous task completes, whereas with promises the executing function returns a special object to you (the promise) and then you tell the promise what to do when the asynchronous task completes.
That is, instead of providing a function reference as an argument to asyncFunc (as you would with callbacks), asyncFunc immediately returns a promise to you, and then you provide the action to be taken when the asynchronous task completes to this promise (through its then method).

https://itnext.io/javascript-promises-vs-rxjs-observables-de5309583ca2