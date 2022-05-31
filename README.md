# Frontend Mentor - Stats preview card component solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#What-I-Learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#Acknowledgments)

## Overview

### the-challenge

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### Screenshot
<p align="center">
<img src="https://user-images.githubusercontent.com/78083890/171156420-6a57560f-7ddb-40e3-ac05-5e73fe715c15.png" alt="desktop preview">
</p>

### Links

- Solution URL: [FrontMentor](https://www.frontendmentor.io/solutions/responsivestatspreviewcardcomponent-gwB_pJ8fJN)
- Live Site URL: [Github Pages](https://zenab12.github.io/stats-preview-Card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox(Responsive)
- Grid Template


### What-I-Learned

- I learned to make overlay above image in smart way and make image responsive 

```
<div class="image stats-preview__img-wrapper">
      <img src="images/image-header-desktop.jpg" class="image-Desktop" alt="image Header">
</div>
```

```
.stats-preview__img-wrapper {
    background-color: var(--Soft-violet-accent);
    overflow: hidden;
}

.stats-preview__img-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    mix-blend-mode: multiply;
    opacity: 75%;
}

```

### Continued development
I will use flexbox and grid template in comming Challenges with Allah willing  in professional way.


### Useful resources

- [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me for refreshing my info about flex in smart way. I really liked this guide and will use it going forward.
- [Grid Template](https://css-tricks.com/snippets/css/complete-guide-grid/)


## Author

- Frontend Mentor - [@zenab12](https://www.frontendmentor.io/profile/zenab12)
- Twitter - [@zenabmo90454136](https://twitter.com/zenabmo90454136)
- Linkedin -[@zenab-mohamed-23133a1a1](https://www.linkedin.com/in/zenab-mohamed-23133a1a1/)


## Acknowledgments

[Bayoumi-dev](https://www.frontendmentor.io/profile/Bayoumi-dev) helped me to use smart way in making overlay so thanks for him
