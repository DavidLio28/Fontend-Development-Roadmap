# JavaScript Basics for Interns

Welcome to the JavaScript basics guide for interns! This document is designed to provide you with the foundational knowledge and skills you need to get started with JavaScript, the programming language of the web. By the end of this guide, you will have a solid understanding of JavaScript fundamentals and be able to create simple interactive web pages.

## Table of Contents

- [Introduction to JavaScript](#introduction-to-javascript)
  - [What is JavaScript?](#what-is-javascript)
  - [Embedding JavaScript in HTML](#embedding-javascript-in-html)
- [Basic JavaScript Concepts](#basic-javascript-concepts)
  - [Variables and Data Types](#variables-and-data-types)
  - [Operators](#operators)
  - [Control Structures](#control-structures)
  - [Functions](#functions)
- [Working with the DOM](#working-with-the-dom)
- [Basic JavaScript Project](#basic-javascript-project)
- [Additional Resources](#additional-resources)

## Introduction to JavaScript

### What is JavaScript?

JavaScript is a versatile, high-level programming language that is an essential part of web development. It allows developers to create dynamic and interactive web pages by manipulating the Document Object Model (DOM), handling events, and interacting with servers.

### Embedding JavaScript in HTML

There are several ways to include JavaScript in an HTML document:

1. **Inline JavaScript**: Using the `onclick` attribute within an HTML element.
    ```html
    <button onclick="alert('Hello, World!')">Click me</button>
    ```

2. **Internal JavaScript**: Using the `<script>` element inside the `<head>` or `<body>` section.
    ```html
    <script>
      alert('Hello, World!');
    </script>
    ```

3. **External JavaScript**: Linking to an external JavaScript file.
    ```html
    <head>
      <script src="script.js"></script>
    </head>
    ```
    In `script.js`:
    ```javascript
    alert('Hello, World!');
    ```

## Basic JavaScript Concepts

### Variables and Data Types

Variables in JavaScript are used to store data. You can declare a variable using `var`, `let`, or `const`.

```javascript
let name = 'John'; // String
const age = 30; // Number
var isStudent = true; // Boolean
