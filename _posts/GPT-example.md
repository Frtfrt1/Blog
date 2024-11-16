---
layout: post
title: "How to Customize Minima Theme"
date: 2024-11-17
categories: [Jekyll, GitHub Pages, Minima]
---

Customizing the **Minima theme** is a great way to give your GitHub Pages site a unique look. This guide will walk you through the steps and demonstrate some styling enhancements.

## What is Minima?

Minima is the default theme for Jekyll, used by many GitHub Pages sites. While it looks clean and professional out of the box, it’s easy to modify using SCSS.

### Custom Styles in Action

Here’s an example of the heading styling:

```scss
h1, h2, h3, h4, h5, h6 {
  font-family: $header-font;
  color: $primary-color;
}
```
