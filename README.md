# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges helps improve ones coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Screenshot

![Screenshot](/images/Screenshot.png "This is a Screenshot of the solution.")

### Links

- Solution URL: [Github](https://www.github.com/simmax456/)
- Live Site URL: [Netlify](https://myqrcodecomponent.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow


### What I learned

I tried using flex properties to align my container to the center vertically to no success, so i took to our neighbourhood friend - google.

I came across the css transform property in the process of searching for a way to align my container vertically and horizontally.

I achieved the vertical and horizontal centering of the container with the code snippet below

```css
.container {
    background-color: var(--White);
    border-radius: 20px;
    width: 320px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%); 
}
```

### Continued development

In the future, i want to properly understand how to properly handle/structure layouts and contents using both flex and css grid.


## Author

- Frontend Mentor - [@simmax456](https://www.frontendmentor.io/profile/simmax456)
- Github - [@simmax456](https://www.github.com/simmax456/)
