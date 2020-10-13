+++
date = "2019-05-29T02:50:52+02:00"
draft = false
title = "Here is my brain-dump for some of practical things"

+++

# Multi-threading programming in C# notes:
Thread safety removes the following conditions in the code:

- **Race condition** occurs when two threads access a shared variable at the same time. The first thread reads the variable, and the second thread writes to the same variable at the same time.

- **Deadlock** case happens in concurrent or multi-threaded environment. It is kind of a situation in which two or more competing threads or tasks wait for the other task to finish and they never finish.

Is the C# Static Constructor Thread -Safe?

- Yes, using a Static Constructor actually is Thread-Safe.
because Static constructors are guaranteed to be run only once per application domain, before any instances of a class are created or any static members are accessed.

Is C# Static Method Thread-Safe?

- No, Static methods are not thread-safe. CLR of C# doesn't thread different than instance method.
 
Is C# Delegate Thread-Safe?
 
- Yes, invoking a Delegate is thread-safe. Since a Delegate is immutable type so it is thread safe. However, modifying event is not thread-safe.