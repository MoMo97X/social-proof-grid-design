# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](preview.jpg)

### Links

- Solution URL: [github](https://github.com/MoMo97X/social-proof-grid-design)
- Live Site URL: [front-end mentor](https://www.frontendmentor.io/profile/MuhammedArrujbani)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

#### 1. Making a clean design.

```html
<main class="wrapper">
  <!-- row-1 -->
  <article class="row header">
    <!-- container-1 -->
    <section class="container hero">
      <!-- elem-1 -->
      <h1></h1>
      <!-- elem-2 -->
      <p></p>
    </section>
    <!-- container-2 -->
    <section class="container rates">
      <!-- elem-1 -->
      <div class="rate reviews"></div>
      <!-- elem-2 -->
      <div class="rate guru"></div>
      <!-- elem-3 -->
      <div class="rate best-tech"></div>
    </section>
  </article>
  <!-- row-2 -->
  <article class="row footer"></article>
</main>
```

#### 2. Handling media queries for different screen

```css
@media (min-width: 40rem) {
}

@media (min-width: 60rem) {
}
```

## Author

- Website - [Github repo](https://github.com/MoMo97X/social-proof-grid-design)
- Frontend Mentor - [@MuhammedArrujbani](https://www.frontendmentor.io/profile/MuhammedArrujbani)
