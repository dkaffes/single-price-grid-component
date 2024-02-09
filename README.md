# Frontend Mentor - Single price grid component solution

This is a solution from Dimitris Kaffes to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

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

## Overview

Mobile-first design was implemented.

I tried to create reusable CSS styles.

There was a first approach to implement CSS custom properties on these Frontend Mentor challenges.

CSS Grid was used for both the mobile and the desktop version. The transform from a single column to a two-column grid was done with a media query. In the media query there are also some `font-size`, `padding` and `margin` changes.

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Screenshot of the solution](./images/screenshot-solution.jpg)

### Links

- Solution URL: [single-price-grid-component solution on Github](https://github.com/dkaffes/single-price-grid-component)
- Live Site URL: [single-price-grid-component live site](https://dkaffes.github.io/single-price-grid-component/)

## My process

I structured the HTML using semantic elements.

The CSS styling was done trying to avoid unnecessary declarations and creating reusable styles.

CSS custom properties were used for the colors and the font weights.

A mobile-first approach was followed.

CSS Grid was implemented for both mobile and desktop versions.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

Custom properties, set using the custom property syntax and accessed using the CSS `var()` function.

Better understanding of the CSS Grid and the basic properties used for the Grid container and the Grid items.

### Continued development

Learn more about CSS naming conventions and their application.

Further investigate the comparison between Flexbox and Grid, and best layout choice depending on the use-case.

### Useful resources

- [Using CSS custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - This MDN article gave me the basic understanding for the first implementation of custom properties.
- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - A detailed guide for the CSS Grid and its usage.

## Author

- Frontend Mentor - [@dkaffes](https://www.frontendmentor.io/profile/dkaffes)
