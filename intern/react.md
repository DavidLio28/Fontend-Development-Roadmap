# React Basics for Interns

Welcome to the React basics guide for interns! This document is designed to provide you with the foundational knowledge and skills needed to get started with React, a popular JavaScript library for building user interfaces. By the end of this guide, you will understand React's core concepts and be able to create your first React application.

## Table of Contents

- [Introduction to React](#introduction-to-react)
  - [What is React?](#what-is-react)
  - [Why Use React?](#why-use-react)
- [React Basics](#react-basics)
  - [Components](#components)
  - [JSX](#jsx)
  - [Props and State](#props-and-state)
  - [Event Handling](#event-handling)
  - [Lifecycle Methods](#lifecycle-methods)
- [Building a Simple React Application](#building-a-simple-react-application)
- [Additional Resources](#additional-resources)

## Introduction to React

### What is React?

React is a declarative, efficient, and flexible JavaScript library for building user interfaces. Developed and maintained by Facebook, React allows developers to build reusable UI components and manage the state of applications in a more predictable way.

### Why Use React?

React offers several benefits, including:

- **Component-Based Architecture**: Build encapsulated components that manage their own state and compose them to make complex UIs.
- **Declarative Views**: Describe what the UI should look like at any given point in time, and React will manage the rendering.
- **Efficient Updates**: React uses a virtual DOM to optimize and minimize direct manipulation of the real DOM, improving performance.
- **Rich Ecosystem**: A wide range of libraries and tools to enhance your development experience (e.g., React Router, Redux).

## React Basics

### Components

Components are the building blocks of a React application. They are reusable pieces of code that represent parts of the user interface. There are two types of components:

- **Functional Components**: Simple components that are defined as JavaScript functions.
    ```javascript
    function Greeting(props) {
        return <h1>Hello, {props.name}!</h1>;
    }
    ```

- **Class Components**: More complex components that are defined as ES6 classes.
    ```javascript
    class Greeting extends React.Component {
        render() {
            return <h1>Hello, {this.props.name}!</h1>;
        }
    }
    ```

### JSX

JSX (JavaScript XML) is a syntax extension for JavaScript that looks similar to HTML. It is used to describe what the UI should look like. JSX gets transpiled into regular JavaScript by tools like Babel.

```javascript
const element = <h1>Hello, world!</h1>;
