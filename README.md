# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

This is a challenge where you can practice making page level layouts. If you want to level up your responsive design skills to a another level, building this challenge is the way to go. It helps you discover more techniques on positioning elements and creating layouts.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/responsive-skilled-e-learning-landing-page-using-flexbox-and-grid-Now3Q_17WA](https://www.frontendmentor.io/solutions/responsive-skilled-e-learning-landing-page-using-flexbox-and-grid-Now3Q_17WA)
- Live Site URL: [https://schindlerdumagat.github.io/skilled-e-learning-landing-page/](https://schindlerdumagat.github.io/skilled-e-learning-landing-page/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [BEM](https://getbem.com/) - Block, Element, Modifier

### What I learned

I learned how to use the picture element to choose the most appropriate image based on the users device.
```html
<picture class="hero__img-container">
  <source srcset="assets/image-hero-desktop.webp 1x, assets/image-hero-desktop@2x.webp 2x" type="image/webp" media="(min-width: 64em)" width="1046" height="938">
  <source srcset="assets/image-hero-desktop.png 1x, assets/image-hero-desktop@2x.png 2x" type="image/png" media="(min-width: 64em)" width="1046" height="938">
  <source srcset="assets/image-hero-tablet.webp 1x, assets/image-hero-tablet@2x.webp 2x" type="image/webp" media="(min-width: 48em)" width="695" height="723">
  <source srcset="assets/image-hero-tablet.png 1x, assets/image-hero-tablet@2x.png 2x" type="image/png" media="(min-width: 48em)" width="695" height="723">
  <source srcset="assets/image-hero-mobile.webp 1x, assets/image-hero-mobile@2x.webp 2x" type="image/webp" width="435" height="409">
  <source srcset="assets/image-hero-mobile.png 1x, assets/image-hero-mobile@2x.png 2x" type="image/png" width="435" height="409">
  <img class="hero__img" src="assets/image-hero-mobile.png" alt="A girl drinking a coffee and in front of it displays the information about the course hours which is 1,451 and the number of members is 29k." width="435" height="409"/>
</picture>
```

I learned some ways on how to position images accurately using absolute positioning and the translate function.
```css
.hero__img-container {
    position: absolute;
    right: 0;
    transform: translate(49%, -11%);
  }
```

## Author

- Website - [Schindler Dumagat](https://schindlerdumagat.github.io/webportfolio/)
- Frontend Mentor - [@schindlerdumagat](https://www.frontendmentor.io/profile/schindlerdumagat)
- LinkedIn - [@schindler-dumagat-015238230](https://www.linkedin.com/in/schindler-dumagat-015238230/)
