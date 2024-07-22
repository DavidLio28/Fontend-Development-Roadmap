# JavaScript for Middle Developers

Welcome to the JavaScript guide for middle developers! This document covers advanced JavaScript concepts and best practices to help you write efficient, maintainable, and high-quality code.

## Table of Contents

- [Advanced Syntax and Features](#advanced-syntax-and-features)
  - [Destructuring](#destructuring)
  - [Spread and Rest Operators](#spread-and-rest-operators)
  - [Async/Await](#asyncawait)
  - [Modules](#modules)
- [Functional Programming](#functional-programming)
  - [Higher-Order Functions](#higher-order-functions)
  - [Closures](#closures)
  - [Currying](#currying)
- [Error Handling](#error-handling)
  - [Try/Catch](#trycatch)
  - [Custom Errors](#custom-errors)
- [Performance Optimization](#performance-optimization)
  - [Debouncing and Throttling](#debouncing-and-throttling)
  - [Memory Management](#memory-management)
- [Additional Resources](#additional-resources)

## Advanced Syntax and Features

### Destructuring

Destructuring allows you to extract values from arrays or properties from objects into distinct variables.

**Example:**

```javascript
// Array Destructuring
const [a, b, c] = [1, 2, 3];
console.log(a); // 1
console.log(b); // 2

// Object Destructuring
const { name, age } = { name: 'Alice', age: 30 };
console.log(name); // Alice
console.log(age); // 30
