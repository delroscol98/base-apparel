# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot

![](./screenshots/desktop.png)
![](./screenshots/mobile.png)

### Links

- Solution URL: [Github](https://github.com/delroscol98/base-apparel)
- Live Site URL: [Github Pages](https://delroscol98.github.io/base-apparel/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- Sass

### What I learned

Simple but powerful form validation.

```html
<input
  type="email"
  class="announcement__input paragraph"
  placeholder="Email address"
  id="email"
/>
```

An example of using mixins and advanced CSS

```css
&__input:placeholder-shown ~ &__label {
  @include hideEl;
  transform: translateY(2rem);
}
```

### Continued development

This was my first time using Sass by myself after completing a course. Challenging but fun.
Forms, in general, are a weakness as there is a lot of validation and logic needed. If I can learn how to use HTML and CSS to help with that logic, it makes things easier.

## Author

- Frontend Mentor - [@delroscol98](https://www.frontendmentor.io/profile/delroscol98)
