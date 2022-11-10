---
title: "Arrow Function"
date: 2020-11-10T00:08:25-08:00
draft: false
---

#### *Main benefit:* 

- No binding of **'this'**  
ES6 arrow functions can’t be bound to a this keyword, so it will lexically go up a scope, and use the value of this in the scope in which it was defined.

- **No self-referencing**  
If your function needs to have a self-reference at any point (e.g. recursion, event handler that needs to unbind), it will not work.

Arrow functions shine best with anything that requires this to be bound to the context, and not the function itself.  

Despite the fact that they are anonymous, I also like using them with methods such as map and reduce, because I think it makes my code more readable. To me, the pros outweigh the cons.


"Arrow functions are (mostly) just "syntactic sugar" for conventional function declarations. There is no performance difference." - https://stackoverflow.com/questions/44030645/are-arrow-functions-faster-more-performant-lighter-than-ordinary-standalone-f/44031830#44031830