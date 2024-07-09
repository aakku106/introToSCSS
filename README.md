# Introduction to SCSS

## Overview

SCSS (Sassy CSS) is an extension of CSS that enables you to use variables, nested rules, mixins, functions, and more, all in a CSS-like syntax. SCSS is fully compatible with CSS syntax, making it easy to adopt for those who are already familiar with CSS.

This project aims to provide a basic understanding of SCSS, its features, and how to use it to write more efficient and maintainable stylesheets.

## Features

- **Variables**: Store colors, font stacks, or any CSS value you think you'll want to reuse.
- **Nesting**: Nest your CSS selectors in a way that follows the same visual hierarchy of your HTML.
- **Partials**: You can create partial SCSS files that contain little snippets of CSS that you can include in other SCSS files.
- **Import**: Use the `@import` directive to include the content of one file in another.
- **Mixins**: Write reusable pieces of CSS code.
- **Functions**: Define complex operations on colors and other values.
- **Inheritance**: Share a set of CSS properties from one selector to another.
- **Operators**: Perform mathematical operations with CSS values.

## Getting Started

To get started with SCSS, you need to have Node.js installed on your computer. Once Node.js is installed, you can install Sass using npm by running the following command in your terminal:

```bash
npm install -g sass
        sass source/stylesheets/index.scss build/stylesheets/index.css
```
### Example
```
    $primary-color: #333;

body {
  font: 100% Helvetica, sans-serif;
  color: $primary-color;
}

nav {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  li { display: inline-block; }

  a {
    display: block;
    padding: 6px 12px;
    text-decoration: none;
  }
}
```
