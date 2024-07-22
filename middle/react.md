# React for Middle Developers

Welcome to the React guide for middle developers! This document covers advanced React concepts and best practices to help you build robust and scalable React applications.

## Table of Contents

- [Advanced Components](#advanced-components)
  - [Class vs Functional Components](#class-vs-functional-components)
  - [Component Composition](#component-composition)
  - [Error Boundaries](#error-boundaries)
- [State Management](#state-management)
  - [Context API](#context-api)
  - [Redux](#redux)
- [Hooks](#hooks)
  - [Custom Hooks](#custom-hooks)
  - [useReducer](#usereducer)
- [Performance Optimization](#performance-optimization)
  - [Memoization](#memoization)
  - [Code Splitting](#code-splitting)
- [Testing](#testing)
  - [Unit Testing](#unit-testing)
  - [Integration Testing](#integration-testing)
- [Additional Resources](#additional-resources)

## Advanced Components

### Class vs Functional Components

- **Class Components**: Use ES6 classes to create components. They have lifecycle methods and state management capabilities.
- **Functional Components**: Use functions to create components. They are simpler and can use hooks for state and lifecycle management.

**Example:**

```javascript
// Class Component
class MyComponent extends React.Component {
    constructor(props) {
        super(props);
        this.state = { count: 0 };
    }

    render() {
        return (
            <div>
                <p>Count: {this.state.count}</p>
                <button onClick={() => this.setState({ count: this.state.count + 1 })}>Increment</button>
            </div>
        );
    }
}

// Functional Component with Hooks
const MyComponent = () => {
    const [count, setCount] = React.useState(0);

    return (
        <div>
            <p>Count: {count}</p>
            <button onClick={() => setCount(count + 1)}>Increment</button>
        </div>
    );
};
