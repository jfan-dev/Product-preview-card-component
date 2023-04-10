# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Solution Screenshot](images/Frontend%20Mentor%20-%20Product%20preview%20card%20component.jpg)

### Links

- Solution URL: [Github](https://github.com/jfan-dev/Product-preview-card-component)
- Live Site URL: [Github Pages](https://jfan-dev.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

How to create a responsive layout for mobile and web while maintaining the size for various web screen resolutions, noneless how to apply a icon before the text for a button.

```css
.product__buybutton::before {
    background-size: contain;
    background: url("images/icon-cart.svg") no-repeat;
    content: "";
    display: inline-block;
    float: left;
    height: 20px;
    width: 20px;
}
```

### Continued development

I need to improve my knowledge of the css units and the best case for each use, need to use more comments for future reference and the right time to git commit the code.

## Author

- E-Mail - [Jaime Fernandes](jfan.dev@gmail.com)
- Frontend Mentor - [@jfan-dev](https://www.frontendmentor.io/profile/jfan-dev)

## Acknowledgments

I want to send a shout-out for my Mother, my Aunts and especially for you Xuxa!


