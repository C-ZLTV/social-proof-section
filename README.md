# Frontend Mentor - Social proof section solution

This is my solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA).

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

Build out this social proof section and get it looking as close to the design as possible.

Users should be able to view the optimal layout for the section depending on their device's screen size.

### Screenshot

![](../screenshots/desktop.png)
![](../screenshots/mobile-cards.png), (../screenshots/mobile-hero.png)

### Links

- Solution: [Solution URL here](https://www.frontendmentor.io/solutions/social-proof-section-x5WwDPe0F-)
- Live Site: [Live site URL here](https://c-zltv.github.io/social-proof-section/)

## My process

I build the social proof section taking the mobile first approach and mainly using Flexbox for the layout. The two parts, hero and cards, became flex containers on the desktop version while on the mobile version all the components fall in a column.

The star ratings layout was made with self-align applied to all three flex items. While the five starts are the svg background image applied to a div with background-repeat on space and a fixed width and height.

The cards have transform on translateY() for the scale effect.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - CSS extension language

### What I learned

This project helped me understand and play around with background properties and values:

```css
background-image: url("../images/bg-pattern-top-mobile.svg"),
  url("../images/bg-pattern-bottom-mobile.svg");
background-position: top left, bottom left;
background-repeat: no-repeat;
background-size: 100%;
```

I also got to implement translateY for the into an actual project and in a useful way:

```css
.card-2 {
  transform: translateY(1rem);
}

.card-3 {
  transform: translateY(2rem);
}
```

## Author

- Website - [Cristina Zlatov](https://c-zltv.github.io/html-css-website/)
- Frontend Mentor - [@C-ZLTV](https://www.frontendmentor.io/profile/C-ZLTV)
- Twitter - [@czltv](https://twitter.com/czltv)
