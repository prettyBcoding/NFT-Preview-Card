# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![My solution preview](https://raw.githubusercontent.com/prettyBcoding/NFT-Preview-Card/main/screenshot.png)


### Links

- Solution URL: https://raw.githubusercontent.com/prettyBcoding/NFT-Preview-Card/main/screenshot.png
- Live Site URL: https://prettybcoding.github.io/NFT-Preview-Card/

## My process

### Built with

- Semantic HTML5 markup
- CSS properties
- Hover overlay effect 

### What I learned

My major learning while working through this project was to put the hover states for the equilibrium image.
Look how I did it:

```html
<img class="image-equilibrium" src="images/image-equilibrium.jpg" alt="NFT Equilibrium image">
<div class="overlay">
  <img class="i-view" src="images/icon-view.svg" alt="">
</div>
```
```css
.overlay{
  background-color: #00fff7;
  border-radius: 0.5rem;
  position: relative;
  bottom: 283px;
  left: 21px;
  width: 17.5rem;
  height: 17.5rem;
  opacity: 0;
  transition: .5s ease;
}

.card:hover .overlay {
  opacity: 0.7;
}

.i-view{
  width: 50px;
  position: relative;
  top: 87px;
  left: 96px;
}

```

**".Card" is the class name of my main element!!!**

### Continued development

I'll still focus on HTML/CSS, to improve my skills. So for now I'll keep doing the challenges of Frontend Mentor untill I get completely comfortable with it.

### Useful resources

- [W3schools](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This helped me how to create an image Hover Overlay.
- [HTML Color Codes](https://developer.mozilla.org/en-US/docs/Web/CSS/) - I used it to convert the HSL color to Hex because the atom was warning about to use HSL.

## Author

- Frontend Mentor - [@prettyBcoding](https://www.frontendmentor.io/profile/prettyBcoding)
- Instagram - [@benolisio](https://www.instagram.com/benolisio)

## Acknowledgments

Thank God to streghten me while I was getting stuck.
Thank to me.
