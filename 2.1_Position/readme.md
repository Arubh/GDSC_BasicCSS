# Understanding CSS Position Property

This example demonstrates the use of the CSS `position` property in web development. If you're a beginner, this README will help you understand how the `position` property affects the layout of HTML elements.

## Description

In the provided HTML and CSS code, we have a simple webpage with various `<div>` elements. Each `<div>` element is styled differently using CSS.

### HTML Structure

- There are several `<div>` elements containing Lorem Ipsum text.

- One of these `<div>` elements has a class of "box1," and it contains another `<div>` element with a class of "box2."

### CSS `position` Property

The CSS `position` property is used to control the positioning of elements on a webpage. In this example, we have included several options for the `position` property as comments within the CSS code. Let's explore these options:

- `position: static;`: This is the default positioning of HTML elements. Elements are displayed in the order they appear in the HTML, and the `top`, `right`, `bottom`, and `left` properties have no effect.

- `position: relative;`: When an element has `position: relative;`, you can use the `top`, `right`, `bottom`, and `left` properties to shift it from its normal position while keeping the space for it reserved.

- `position: absolute;`: Elements with `position: absolute;` are positioned relative to their closest positioned ancestor. If no positioned ancestor is found, they are positioned relative to the initial containing block (usually the viewport).

- `position: fixed;`: Fixed elements are positioned relative to the viewport. They stay in the same place, even when the user scrolls the webpage.

## Usage

1. Clone this repository to your local machine or download the HTML and CSS files.

2. Open the `index.html` file in your web browser.

3. Observe the different positioning effects applied to the "box1" and "box2" elements in the HTML by uncommenting the respective `position` property values in the CSS code.

4. Experiment with different `position` property values to see how they affect the layout and positioning of the elements.

