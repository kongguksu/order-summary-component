# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](screenshot.jpg)

### Links

- Solution URL: [https://github.com/kongguksu/order-summary-component.git]
- Live Site URL: [https://kongguksu.github.io/order-summary-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

I learned to use both an image and a background-color to make the background of the viewport.

```css
html {
  height: 100%;
  background-color: hsl(225, 100%, 94%);
}

body {
  position: relative;
  min-height: 100%;
  font-family: "Red Hat Display", sans-serif;
  font-weight: 500;
  font-size: 1rem;
  line-height: 1;

  background-image: url(../images/pattern-background-desktop.svg);
  background-size: contain;
  background-repeat: no-repeat;
}
```

### Continued development

I used absolute positioning to center the order summary card in the viewport vertically and horizontally.

```css
.order-summary-container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);

  width: 24rem;
  background-color: #fff;
  border-radius: 1.3rem;
  box-shadow: 0 1rem 2rem rgba(114, 128, 167, 0.2);
}
```

## Author

- Frontend Mentor - [@kongguksu](https://www.frontendmentor.io/profile/kongguksu)
