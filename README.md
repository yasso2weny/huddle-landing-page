# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Built with

- HTML
- CSS Grid

### What I learned

Using Grid

```css
.container {
    display: grid; /* Creating a grid container */
    /* Defining the columns and rows of the grid */
    grid-template-columns: 1fr 1fr; /* Two columns of equal width */
    grid-template-rows: auto 1fr auto; /* Three rows */
    /* Defining the layout of the grid */
    grid-template-areas: 
      "header header" /* The first row will span across both columns */
      "left right" /* The second row will have a left and right area */
      "footer footer"; /* The third row will span across both columns */
    height: 100vh; /* To fill the viewport */
  }
```
### Useful resources

- [Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) 
- [hex to css filter](https://isotropic.co/tool/hex-color-to-css-filter/) 

## Author

- Programmer - [Yassin Mohamed]

