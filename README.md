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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./Screenshot.png)


### Links

- Solution URL: https://github.com/oanh-hth/FMS-Single_Price_Component
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

Try to use 'calc()' function for fluid typography, applied for h1, h2 font-size property

To see how I can add code snippets, see below:

```html

<h1>Join our community</h1>
...
<h2>30-day, hassle-free money back guarantee</h2>

```
```css

h1 {
  font-size: calc(20px + 4 * (100vw - 375px) / 1065);
}

h2 {
  font-size: calc(15px + 3 * (100vw - 375px) / 1065);

}

```


### Useful resources

- [CSS Trick](https://css-tricks.com/snippets/css/fluid-typography/) - This helped me for finding out a formular applied in calc() function

## Author

- Frontend Mentor - [@oanh-hth](https://www.frontendmentor.io/profile/oanh-hth)
