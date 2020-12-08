---
title: "Tdd Test Programming"
date: 2020-12-08T10:45:08-08:00
draft: true
---

- **Unit Tests**: Test individual components in isolation from environment and concrete dependencies
- **Integration Tests**: Test how concrete components work together within a given subsystem
- **End-to-End Tests**: Test the behavior of an entire system with all parts functioning together  

Distinguish these tests from Automated UI Tests (see below) if I am driving the system via an API instead of a GUI.

- **Automated UI Tests**: These are commonly used for web-based projects, filling a couple of different roles:
- **Content-based Testing**: Verifies that the visual, content, and layout properties of a given view are correct
- **Functional Testing**: Verifies end-to-end functionality by driving the UI and verifying (from the UI layer) that the system functions correctly.  

In a nutshell, one's selection of testing strategies and tools depends on a variety of factors and tends to vary for each project.

Unit testing actors:
- System Under Test (SUT): This is the code you want to test. In .NET unit testing, this is usually in a class library.
- Test Suite: A logical grouping of all the tests for a given system (e.g. "The app's test suite comprises over 9,000 tests")
- Test Fixture: This is a class containing tests that exercise the features of the SUT.
- Test Runner: This is a tool specific to whichever testing framework you are using. It provides an environment in which Test Suites can be loaded, executed, and verified.

Don't do when writing unit test in .NET:

- Don't write tests for Plain Old CLR Objects (POCOs) - POCOs are data transfer objects and should not have behaviors.
- Don't test code that is purely a wrapper over a .NET Framework object (i.e. Directory, File, etc.) - If a class is a pure wrapper (not adding any new or behavior), unit tests end up just testing the .NET Framework, which is not our responsibility.