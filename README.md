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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Design preview for the Product preview card component coding challenge - Desktop Mode](./design/desktop.png)

![Design preview for the Product preview card component coding challenge - Mobile Mode](./design/mobile.png)

### Links

- Live Site URL: [Click here](https://martyofmca.github.io/frontend-mentor-challenge-one/)

## My process

### Built with

- HTML
- CSS (Custom Properties)
- Flexbox
- Mobile-first workflow

### What I learned

Manipulating an element using CSS custom properties was pretty exciting. I could easily change the background image for a div really easily. Custom properties are fun and can be used to solve tons of problems I could have used JavaScript to solve.

```html
<div class="awesome"></div>
```
```css
.awesome {
  --bg-img: url("path to mobile image");
  background-image: var(--bg-img);
}

@media (min-width: 760px) {
  .awesome {
    --bg-img: url("path to desktop image");
  }
}
```

### Useful resources

- [Kevin Powell](https://www.kevinpowell.co/) - Really helped shaped my understanding in modern CSS design. I would definetely recommend him to anyone who really wants to step up their CSS game.

## Author

- Frontend Mentor - [@MartyOfMCA](https://www.frontendmentor.io/profile/MartyOfMCA)
- Twitter - [@martyofmca](https://twitter.com/martyofmca)