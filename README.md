# Frontend Mentor - Testimonials grid section solution

![](./design/desktop-preview.jpg)

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

## My process

### Built with

- Semantic HTML5 markup
- Grid Layout
- [SASS](https://sass-lang.com/documentation/modules) - Sass modules

### Useful resources

- [Material Design Box Shadows](https://codepen.io/sdthornton/pen/wBZdXq)
- [CSS background Property](https://www.w3schools.com/cssref/css3_pr_background.asp)
- [BEM naming convention](https://css-tricks.com/bem-101/)
- [Solving Sticky Hover States with @media (hover: hover)](https://css-tricks.com/solving-sticky-hover-states-with-media-hover-hover/)

## Author

- Frontend Mentor - [@melvinaguilar](https://www.frontendmentor.io/profile/melvinaguilar)

## Acknowledgments

When using `sass` in order to build this solution

- Install `sass` if not yet installed:

```bash
npm install -g sass
```

- Run build command from command line:

```bash
sass assets/sass/main.scss assets/css/style.css
```

- If you want to edit the code and test, in the root folder of this repository, run this command from the command line:

```bash
sass --watch assets/sass/main.scss assets/css/style.css
```

## File structure

```
.
├── assets
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── images
│   │   ├── bg-pattern-quotation.svg
│   │   ├── favicon-32x32.png
│   │   ├── image-daniel.jpg
│   │   ├── image-jeanette.jpg
│   │   ├── image-jonathan.jpg
│   │   ├── image-kira.jpg
│   │   └── image-patrick.jpg
│   └── sass
│       ├── abstracts
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base
│       │   ├── _page.scss
│       │   └── _reset.scss
│       ├── component
│       │   ├── _heading.scss
│       │   └── _screen-reader.scss
│       ├── layout
│       │   └── _testimonials-section.scss
│       └── main.scss
├── design
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   └── mobile-design.jpg
├── index.html
└── README.md
```