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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Dekstop view

![](./screenshoot-dekstop.png)

Mobile view

![](./screenshoot-mobile.png)


### Links

- Solution URL: [Repo Github](https://github.com/ardi-cahyono/FrontendMentor-3-Column-Preview-Card.git)
- Live Site URL: [Github Pages](https://ardi-cahyono.github.io/FrontendMentor-3-Column-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Google Fonts
- [Bootstrap](https://getbootstrap.com/) - Bootstrap

### What I learned

In this project finaly I able to centering div horizontal and verticaly and learn some media breakpoint usages.

Centering DIV horizontal and verticaly
```css
body {
 font-family: 'Lexend Deca', sans-serif;
 display: flex;
 flex-direction: column;
 justify-content: center;
 align-items: center;
 min-height: 100vh;
 background-color: hsl(0, 0%, 95%);
}
.row {
 justify-content: center;
}
```
Some media breakpoints usages
```css
@media (max-width: 991.98px) {
 .container {
  padding: 90px 30px 90px 30px;
 }
 .bg-sedans {
  border-radius: 15px 15px 0px 0px;
 }
 .bg-luxury {
  border-radius: 0px 0px 15px 15px;
 }
}

@media (min-width: 991.98px) {
 .bg-sedans {
  border-radius: 15px 0px 0px 15px;
 }
 .bg-luxury {
  border-radius: 0px 15px 15px 0px;
 }
}
```

### Continued development

In the future i want to implement this project with JS Framework such as React.JS

### Useful resources

- [Bootstrap 5 Docs](https://getbootstrap.com/docs/5.0/getting-started/introduction/) - This is an amazing documentation which helped me finally understand css grid system. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Ardi Cahyono](https://ardi-cahyono.github.io)
- Frontend Mentor - [@ardi-cahyono](https://www.frontendmentor.io/profile/ardi-cahyono)

