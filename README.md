# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [Github repo](https://github.com/N1Dovud/Blog-preview)
- Live Site URL: [Live Site](https://n1dovud.github.io/Blog-preview)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid

### What I learned


```css
@font-face {
    font-family: "Figtree";
    src: url(assets/fonts/Figtree-Italic-VariableFont_wght.ttf) format("ttf");
    font-style: italic;
}
@media screen and (min-width: 1440px)
{
    html {
        font-size: 16px;
    }
}
.author {
    display: flex;
    align-items: center;
    gap: 0.75rem;
}
```
- I learned how to apply fonts that exist in my local folder. I learned a lot of fonts themselves like differences between typeface and fonts, variable and static fonts, font family and font styles, format of fonts.
- I think I am now getting the idea behind media queries and using rem for responsiveness. I learned setting the right min width or max width as well as the order at which they should come depending on my preferences. I learned to reset the font size of the root to change the rem font everywhere.
- I realized that to add a gap between items, I can simply use a flexbox and apply the gap property without having to add padding or margin to each individual item.
### Continued development

- * I need to continue to learn about the core difference between flexbox and grid. I should fully master both. Also, I should work on accurately approximating the styles of items with naked eyes.

## Author
- Frontend Mentor - [N1Dovud](https://www.frontendmentor.io/profile/N1dovud)
