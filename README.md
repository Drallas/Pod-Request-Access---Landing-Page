# Frontend Mentor - Four card feature section solution

This is a solution to the [Pod Request Access challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Coding Time : 8 hrs 53 mins

Your users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements
- Receive an error message when the form is submitted if:
  - The `Email address` field is empty should show "**Oops! Please add your email**"
  - The email is not formatted correctly should show "**Oops! Please check your email**"

### Screenshot

![](./assets/screenshot.png)

### Links

- Solution URL: [GitHub](https://github.com/Drallas/Pod-Request-Access---Landing-Page)
- Live Site URL: [GitHub Live](https://drallas.github.io/Pod-Request-Access---Landing-Page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- BEM
- JavaScript

### What I learned

Learning more about the utility of Linear Gradients. The mobile layout for this challenge has a darkened background Image. I first extracted the hex for the color to darken the image from Figma and 'converted' (too easy in VSCode) it to HSLA values. The value from Figma seems a bit too light so i increased value.

```css
background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('landingpagepic.jpg');

```
### Continued development

I need to become more comforatble adding JavaScript components, i know a bit how to code, but i feel some resistance! 

### Useful resources

- [How to Background Image](https://www.codegrepper.com/code-examples/css/how+to+darken+background+image+with+css) - This helped me to create the mobile darkened Background-Image.
- [Pixel to Rem VScode extension](https://github.com/sainoba/vscode-px-to-rem) - Had enough of divding px values / 16, 'Option / Z ' works faster.

## Author

- Frontend Mentor - [@Drallas](https://www.frontendmentor.io/profile/Drallas)
- Dev.to - [@Drallas](https://dev.to/drallas)


