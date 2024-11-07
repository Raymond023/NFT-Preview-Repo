# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://nftcardpreviewfec.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

How to display an image over another one when hover over it.

```html
<img class="equilibrium" src="/images/image-equilibrium.jpg" alt="equilibrium icon">
<img class="eye" src="/images/icon-view.svg" alt="eye icon">
```
```css
    .eye{
      border-radius: 12px;
      background-color: hsl(178, 100%, 50%);
      position: absolute;
      margin-left: -259px;
      margin-top: 20px;
      padding: 110px 100px;
      opacity: 0;
    }
    .eye:hover{
      opacity: 0.5;
    }
    .equilibrium{
      border-radius: 12px;
      margin: 20px 10px 10px 18px;
      font-weight: 600;
      font-size: 15px;
      position: relative;
      height: 270px;
      width: 250px;
    }
```

### Continued development
i look forward to improving my skills on media query (varying resolution)

## Author

- Website - [Raymond Munonye](https://nftcardpreviewfec.netlify.app)
- Frontend Mentor - [@Raymond023](https://www.frontendmentor.io/profile/Raymond023)
- Twitter - [@thegraykid](https://www.twitter.com/thegraykid)