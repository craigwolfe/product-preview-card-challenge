# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

Build a responsive product page using HTML and CSS.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/responsive-product-page-EdTKIP6TBZ)
- Live Site URL: [Github Pages](https://craigwolfe.github.io/product-preview-card-challenge/)

## My process

Of course I start with the HTML first. I setup all of the CSS and Font links. Then I start structuring the HTML. Then I start writing the CSS with first a reset and then all of the global variables like colors, font-size, font-family, font-weight etc. Most of the time I use a combination of Grid and Flexbox.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned about the source srcset image tag that allows you to easily swap out images for different size. I thought I knew a lot about accessibility but the visually-hidden selector was a new one.

```html
<source srcset="./images/image-product-desktop.jpg" media="(min-width:600px)" />
```

```css
.visually-hidden:not(:focus):not(:active) {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}

.button:is(:hover, :focus) {
  background-color: var(--clr-primary-500);
}
```

### Useful resources

- [Taking on a Frontend Mentor challenge | Responsive Product Preview Card Component]<br>(https://www.youtube.com/watch?v=B2WL6KkqhLQ)<br> -[Josh Comeau CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/)<br> -[Visually Hidden](https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html)

## Author

- Frontend Mentor - [@craigwolfe](https://www.frontendmentor.io/profile/craigwolfe)

## Acknowledgments

[Kevin Powell](https://www.youtube.com/watch?v=B2WL6KkqhLQ) was huge help. I really enjoy his video content. Brillant at explaining CSS Grid and Flexbox. I think because of him its really starting to sink in.
