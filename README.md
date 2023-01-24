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
- [Author](#author)

## Overview

Product preview card component

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot of design

![mobile view screenshot](design/Screenshot%202023-01-24%20at%2014-08-19%20Frontend%20Mentor%20Product%20preview%20card%20component.png)
![Desktop view](design/Screenshot%202023-01-24%20at%2014-09-10%20Frontend%20Mentor%20Product%20preview%20card%20component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learnt how to add two different images and allow one appear in mobile and the other in desktop mode only.

```html
<div class="picture-container">
  <img
    class="desktop-only"
    src="images/image-product-desktop.jpg"
    alt="perfume"
  />
  <img
    class="mobile-only"
    src="images/image-product-mobile.jpg"
    alt="perfume"
  />
</div>
```

```css
@media only screen and (min-width: 1025px) {
  .mobile-only {
    display: none;
  }
}
@media only screen and (max-width: 1026px) {
  .desktop-only {
    display: none;
  }
}
```

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/MiriamOkpalaeke)
