---
layout: post
title:  "Whats's the difference between methods and functions?"
date:   2015-06-12 11:38:46
categories: doubts
---
The answer was taken from [StackOverflow question](http://stackoverflow.com/questions/155609/difference-between-a-method-and-a-function).

**Explanation:**

A function is a piece of code that is called by name. It can be passed data to operate on (ie. the parameters) and can optionally return data (the return value).

All data that is passed to a function is explicitly passed.

A method is a piece of code that is called by name that is associated with an object. In most respects it is identical to a function except for two key differences.

It is implicitly passed for the object for which it was called.
It is able to operate on data that is contained within the class (remembering that an object is an instance of a class - the class is the definition, the object is an instance of that data).

A method is on an object.
A function is independent of an object.

For Java, there are only methods.
For C, there are only functions.

For C++ it would depend on whether or not you're in a class.
