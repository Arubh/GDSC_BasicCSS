# Advanced CSS Selectors

In this example, you'll explore advanced CSS selectors used to style various elements within an HTML document. We'll cover pseudo-class selectors, pseudo-element selectors, and attribute selectors to demonstrate how they can be applied to different HTML elements. This README.md will provide explanations for each selector type used in the code.

## Table of Contents

- [Advanced CSS Selectors](#advanced-css-selectors)
  - [Overview](#overview)
  - [HTML Structure](#html-structure)
  - [CSS Selectors](#css-selectors)
    - [Pseudo-class Selectors](#pseudo-class-selectors)
    - [Pseudo-element Selectors](#pseudo-element-selectors)
    - [Attribute Selectors](#attribute-selectors)
  - [Styles Applied](#styles-applied)
  - [Additional Resources](#additional-resources)

## Overview

Advanced CSS selectors allow you to apply styles to specific elements or states of elements in your HTML document. This can be incredibly useful for creating interactive and visually appealing web pages. In this example, we'll explore various advanced selectors and see how they affect different HTML elements.

## HTML Structure

The HTML document (`index.html`) contains a simple structure with various elements such as headings, links, lists, paragraphs, checkboxes, and an image, all contained within a `.container` div.

## CSS Selectors

### Pseudo-class Selectors

- `a:hover`: This selector targets anchor (`<a>`) elements when the mouse pointer is hovering over them (`:hover`). It changes the text color to red when the link is hovered.

- `li:nth-child(odd)`: This selector targets list items (`<li>`) that are odd children within their parent `<ul>`. It applies a light gray background color to these list items.

### Pseudo-element Selectors

- `p::first-line`: This selector targets the first line of paragraphs (`<p>`). It makes the text within the first line bold.

- `p::before` and `p::after`: These selectors target the content before and after paragraphs (`<p>`), respectively. They add green ">> " before and " <<" after the content of paragraphs.

### Attribute Selectors

- `input[type="checkbox"]`: This selector targets input elements of type "checkbox." It adds a right margin to checkboxes.

- `a[href^="https://"]`: This selector targets anchor (`<a>`) elements with `href` attributes that start with "https://". It changes the text color to blue for links with URLs starting with "https://".

- `img[alt="logo"]`: This selector targets images (`<img>`) with an `alt` attribute equal to "logo." It adds a red border and border-radius to these images.

## Styles Applied

The styles applied to various elements within the HTML document include text formatting, padding, margins, border styles, and font choices. The styles are used to create a visually pleasing and well-structured webpage.

## Additional Resources

To learn more about advanced CSS selectors and how to use them effectively, consider exploring the following resources:

- [MDN Web Docs: Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes): Detailed information on pseudo-class selectors.

- [MDN Web Docs: Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements): In-depth coverage of pseudo-element selectors.

- [MDN Web Docs: Attribute selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors): Comprehensive explanation of attribute selectors.

- [CSS Tricks: A Complete Guide to CSS Selectors](https://css-tricks.com/how-css-selectors-work/): An extensive guide on various CSS selectors, including advanced ones.
