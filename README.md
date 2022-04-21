# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I've practiced to build a strong HTML foundation before styling to learn how to give proper class names and organize the structure in a meaningful way, below is the basic HTML structure that I made.

```html
<main>
  <div class="card-container">
    <div class="card-header-background"></div>
    <div class="card-header-profile-picture"></div>
    <div class="card-content"></div>
    <hr />
    <div class="card-footer">
      <div class="card-footer-item"></div>
      <div class="card-footer-item"></div>
      <div class="card-footer-item"></div>
    </div>
  </div>
</main>
```

I also learned the basics to work with backgrounds, below there's a sample of how the background images where placed.

```css
background-image: url("./images/bg-pattern-top.svg"),
  url("./images/bg-pattern-bottom.svg");
background-repeat: no-repeat;
background-position: right 52vw bottom 35vh, 48vw 52vh;
```

### Continued development

I'm going to search more about backgrounds and how to properly implement then specially the modular ones like the two svg provided by this challenge, I'm also interested in learning more about animations, transitions and hover states.

### Useful resources

- [MDN Web Docs :where()](https://developer.mozilla.org/en-US/docs/Web/CSS/:where) - This helped me to understand the basics of the where pseudo-class
- [PX to REM](https://nekocalc.com/px-to-rem-converter) - This helped me to convert px into rem units

## Author

- Frontend Mentor - [@MateusAbelli](https://www.frontendmentor.io/profile/mateusabelli)

## Acknowledgments

In this challenge I have searched for other peoples solutions on github and youtube to help me when I was stuck, specially with the background.

