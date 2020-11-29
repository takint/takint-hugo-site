---
title: "React Optimization"
date: 2020-11-29T11:51:13-08:00
draft: false
---

#### Parent and child components are often re-rendered in the following scenario:
- When setState is called in the same component or parent component.  
- Change in the value of “props” received from a parent.  
- Calling forceUpdate in the component.  

#### **React Performance Optimization** is easy to achieve with the following simple steps.

- Use **React Pure Components** to reduce Re-rendering
- Using **React Hooks** and working with functional programming
- Use `React.memo` for Component Memorization
- Using the `shouldComponentUpdate` Life Cycle Event
- Using Lazy Loading of React Components
- Use React Fragments to Avoid Extra Tag
- **Do Not Use** React Inline Function Definition
- **Avoid** Async Requests in `componentWillMount()`
- Bind Function Early in Constructor
- Arrow Functions vs Binding in Constructors
- **Avoid** Using Inline Style Attribute
- Optimize Conditional Rendering in React
- **Don’t Derive Data** in the Render Method
- Create Error Boundaries for the Components
- Immutable Data Structures for Components
- Using a Unique Key for Iteration
- Throttling and Debouncing Events
- Using CDNs for External Resources
- **CSS Animation** Instead of JavaScript Animation
- Enable gzip Compression on the Web Server
- Use Web Workers for CPU Extensive Tasks
- Server-Side Rendering of the React Component