# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

<img src="https://github.com/DarrickFauvel/fem05-3-column-preview-card-component/blob/main/screenshot-mobile.png" width="200" />
<img src="https://github.com/DarrickFauvel/fem05-3-column-preview-card-component/blob/main/screenshot-desktop.png" width="400" />

### Links

- Solution URL: [https://github.com/DarrickFauvel/fem05-3-column-preview-card-component](https://github.com/DarrickFauvel/fem05-3-column-preview-card-component)
- Live Site URL: [https://fem05-3-column-preview-card-component-drrck.netlify.app/](https://fem05-3-column-preview-card-component-drrck.netlify.app/)

## My process

### Built with

- Mobile-first workflow
- Semantic HTML5 markup
- Flexbox
- [Sass](https://www.sass-lang.com) - CSS with superpowers
- [Parcel](https://parceljs.org) - Zero config build tool

### What I learned

I learned that using the CSS `box-shadow` property with value `inset 0 0 0 2px white` makes a nice button outline on mouse hover.

I've seen people implement this pattern using the CSS `border` property:

```css
.button {
  border: 2px solid transparent;
}
.button:hover {
  border: 2px solid white;
}
```

But I think it's more convenient to use the CSS `box-shadow: inset` method:

```css
.button:hover {
  box-shadow: inset 0 0 0 2px white;
}
```

### Useful resources

- [MDN: box-shadow - CSS Property](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This helped me learn more about the `box-shadow: inset` method.

## Author

- Website - [Darrick Fauvel](https://www.darrickfauvel.com)
- Frontend Mentor - [@DarrickFauvel](https://www.frontendmentor.io/profile/DarrickFauvel)
