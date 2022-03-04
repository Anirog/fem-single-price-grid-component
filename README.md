# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)


### Links

- [Live Site URL](https://anirog.github.io/fem-single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned to use CSS custome properties (variables) for the colours and also the padding, this wasn't really neccesary on a project this size but it will be helpful in future projects. 

Example of CSS variables

```css
/* Variables begin with a double hyphen */

--cyan: hsl(179, 62%, 40%);
--ltcyan: hsl(179, 62%, 45%);
--yellow: hsl(71, 73%, 54%);
```

Then put the variable inside the `var()` function

```css
.community {
    color: var(--yellow);
```

### Continued development

I have a basic understanding of flexbox and CSS grid, but I still don't fully understand it.

### Useful resources

- [Using CSS custom properties (variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This page on the Mozilla Developer Network helped me with CSS custom properties
- [Git Tutorial for Beginners - Git & GitHub Fundamentals In Depth](https://youtu.be/DVRQoVRzMIY) - This YouTube video hepled me create this repository and showed me how to use git and github.

## Author

- Website - [Larrie Knights](https://larrieknights.com)
- Frontend Mentor - [@Anirog](https://www.frontendmentor.io/profile/Anirog)
- Twitter - [@512kilobytes](https://twitter.com/512kilobytes)

## Acknowledgments

Thanks to the excellent YouTube channel [Coder Coder](https://www.youtube.com/c/TheCoderCoder)
