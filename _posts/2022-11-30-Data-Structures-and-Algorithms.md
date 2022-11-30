---
title: Data Structures and Algorithms
date: 2022-11-30 12:00:00 +0100
categories: [school, computer science, career]
tags: [school, career]
---

Today I decided to do some practice with data structures and algorithms in Java.  I decided to write a post going over some of the basics.

## Stacks
Stacks are a Last in First Out data structure.  This is like a stack of items in real life.  The last or "top" item is the first one to come off when you start taking items off the stack.  

To create a stack in java we can use the syntax:

```Java
Stack<String> stack = new Stack<String>();
```

This would create a new instance of the Stack object called "stack".

Methods for working with stacks include push(add), pop(remove) and peek(look at the top but dont remove).  Here are some examples:

```Java
stack.push("Minecraft");
```

```Java
stack.pop();
```

```Java
stack.peek();
```

Check out some code i wrote up working with stacks in Java on my github [here](https://github.com/mgregoire254/Data-Structures-and-Algorithms-Practice)


In my next post we will look at Queues using Java.