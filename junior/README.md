# Junior Frontend Developer Guide

Welcome to the Junior Frontend Developer Guide! This repository is designed to help junior developers build and enhance their skills across various aspects of frontend development. Here you’ll find resources, best practices, and practical examples to guide you through essential topics.

## Table of Contents

- [Introduction](#introduction)
- [HTML & CSS](#html--css)
- [JavaScript](#javascript)
- [React](#react)
- [Tools](#tools)
- [Performance](#performance)
- [Contributing](#contributing)
- [Additional Resources](#additional-resources)

## Introduction

As a junior frontend developer, you are expected to have a solid understanding of HTML, CSS, JavaScript, and commonly used tools and frameworks. This guide will help you sharpen your skills and improve your understanding of these core technologies.

## HTML & CSS

### HTML

- **Semantic HTML**: Use HTML5 semantic elements (e.g., `<header>`, `<footer>`, `<article>`) to structure your content.
- **Forms and Input Types**: Understand various input types and form elements for user interaction.

**Example:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Example</title>
</head>
<body>
    <form action="/submit" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="age">Age:</label>
        <input type="number" id="age" name="age">
        
        <button type="submit">Submit</button>
    </form>
</body>
</html>
