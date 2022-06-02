# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](/images/Screenshot.png)

### Links

- Solution URL: [https://github.com/BLBarricklow/Frontend-Mentor---QR-code-component](https://github.com/BLBarricklow/Frontend-Mentor---QR-code-component)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This was mainly a refresher on HTML and CSS, but I did hit a couple snags. I need to remember to define the body's height in an absolute value, like viewheight, to allow the responsive units and flexbox to work as expected. In particular, the body's height only grew to fit the content inside before using 100vh. That prevented justify-content from centering the card vertically (I used a column layout to prevent the credits link from moving to the side of the qr card, that's why the main axis was vertical).

### Continued development

- Get more comfortable with flexbox
- Get more understanding and experience with CSS clamp
- Explore more options for confirming accuracy to the design document

### Useful resources

- [CSS-Tricks Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - A great tutorial for flexbox and one of my favorite quice references for the various options flexbox provides.
- [Kevin Powell](https://www.youtube.com/watch?v=U9VF-4euyRo) - This video on min, max, and clamp() is the first time I've heard of them. It's a great primer for the three.

## Author

- Website - [Brandon Barricklow](https://blbarricklow.netlify.app/)
- Frontend Mentor - [@BLBarricklow](https://www.frontendmentor.io/profile/BLBarricklow)
- Twitter - [@blbarricklow](https://twitter.com/blbarricklow)
