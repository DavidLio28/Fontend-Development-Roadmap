# HTML & CSS for Junior Developers

Welcome to the HTML & CSS guide for junior developers! As a junior frontend developer, you should be comfortable with advanced HTML and CSS concepts and practices. This guide covers essential skills and techniques to help you build and style complex web pages and applications.

## Table of Contents

- [Advanced HTML](#advanced-html)
  - [Semantic HTML](#semantic-html)
  - [Forms and Input Types](#forms-and-input-types)
  - [Accessibility](#accessibility)
- [Advanced CSS](#advanced-css)
  - [Flexbox](#flexbox)
  - [CSS Grid](#css-grid)
  - [Animations and Transitions](#animations-and-transitions)
  - [Preprocessors](#preprocessors)
- [Best Practices](#best-practices)
- [Additional Resources](#additional-resources)

## Advanced HTML

### Semantic HTML

Semantic HTML elements provide meaning to the web content and improve accessibility and SEO. Some key semantic elements include:

- `<header>`: Represents introductory content or navigational links.
- `<nav>`: Defines a set of navigation links.
- `<article>`: Represents a self-contained composition.
- `<section>`: Defines a section in a document.
- `<aside>`: Represents content indirectly related to the main content.
- `<footer>`: Represents the footer of a section or document.

**Example:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic HTML Example</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <article>
            <h2>Article Title</h2>
            <p>This is an article.</p>
        </article>
        <aside>
            <h2>Related Information</h2>
            <p>This is some related information.</p>
        </aside>
    </main>
    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>
</body>
</html>
