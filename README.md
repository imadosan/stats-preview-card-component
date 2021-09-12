# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot of the site](./images/screenshot.png)

### Links

- Solution URL: [Click to visit](https://www.frontendmentor.io/solutions/statspreviewcardcomponent-css-grid-and-flexbox-lZiPhGggE)
- Live Site URL: [Click to visit](https://imadosan.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Using the picture element to show different images depending on the viewport width

```html
<picture>
  <source
    srcset="images/image-header-desktop.jpg"
    type="image/jpg"
    media="(min-width: 950px)"/>
  <img src="images/image-header-mobile.jpg" alt="image of people working" />
</picture>
```

## Author

- Frontend Mentor - [@imadosan](https://www.frontendmentor.io/profile/imadosan)
