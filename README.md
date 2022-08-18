# Frontend Mentor - Four card feature section

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

- Build out the project to the designs provided.

### Screenshot

# Mobile Preview 

![screenshot](https://github.com/romila2003/Four-Card-Feature-Section/blob/main/Mobile%20preview.PNG)

# Tablet Preview

![screenshot](https://github.com/romila2003/Four-Card-Feature-Section/blob/main/Tablet%20preview.PNG)

# Desktop Preview 

![screenshot](https://github.com/romila2003/Four-Card-Feature-Section/blob/main/Desktop%20preview.PNG)


### Links

 - Source code: [https://github.com/romila2003/Four-Card-Feature-Section](https://github.com/romila2003/Four-Card-Feature-Section)
 - Live website: [https://four-card-feature-section-main.netlify.app/](https://four-card-feature-section-main.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Flexbox
- Grid
- Mobile-first workflow

### What I learned

This challenge allowed me to work with CSS grid and really develop my skills using Grid. I learnt more about `grid-template-areas` and was able to rearrange the cards according to the grid-area. It was difficult to have the first (supervisor) and last card (calculator) position in the middle of its column, next to the card like the design therefore I used the `top` and `bottom` property to center the boxes. Overall, it was a fun project to work with HTML and CSS along, particularly the CSS Grid.

CSS - `grid`: 

```css

@media screen and (min-width: 1000px) {
    .boxes {
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(2, 1fr);
        grid-template-areas: 
        "a b c" 
        "d e f";
    }

    .box {
        padding-bottom: 8em;
    }

    .box:first-of-type {
        grid-area: a;
        top: 10em;
    }

    .box:nth-child(2) {
        grid-area: b;
    }
    
    .box:nth-child(3) {
        grid-area: e;
    }
    
    .box:last-of-type {
        grid-area: f;
        bottom: 7em;
    }
}

```

### Continued development

For future developments, I need to learn more complex concepts and utilise those within future projects. Also, I should form a habit of writing clean codes in HTML regarding the semantics as well as Javascript, to prevent repetitive codes and to make it easier to read. Also, I should begin taking on more challenging responsive projects to test my layout skills. 


## Author

- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
- Twitter - [@romila003](https://www.twitter.com/romila003)
