# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- This is my solution to the challenge provided to me by Frontend Mentor

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Solution URL](https://github.com/Aya333/Huddle)
- Live Site URL: [Live site URL](https://aya333.github.io/Huddle/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have learned how to work with positioning and why it's important because I have always struggled to understand them, also I have tried using different CSS units and that worked magically for me not to mention that it's my first time using media queries and I did my best to figure out what parts do break & when it happens, I mean at what breaking point only using "Inspect"

```html
<h1>Some HTML code I'm proud of</h1>
!-- Showcase -->
<section class="showcase">
  <div class="grid-col-1">
    <h1>
      Build the community <br />
      your fans will love
    </h1>
    <p>
      Huddle re-imagines the way we build communities. You have a voice, but so
      does your audience. Create connections with your users as you engage in
      genuine discussions.
    </p>
    <button class="showcase-btn">Get Started For Free</button>
  </div>
  <div class="grid-col-2">
    <img src="images/illustration-mockups.svg" alt="" />
  </div>
</section>
```

```css
.proud-of-this-css {
  .extra-card {
    width: 40vw;
    height: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    background-color: #fff;
    border: 1px solid #bbb;
    border-radius: 1.2rem;
    margin: 1rem auto;
    padding: 2rem;
    font-family: "Open Sans", sans-serif;
    position: absolute;
    left: 30%;
    top: 80%;
  }
}
```

### Continued development

I want to further Improve the responsive part of css and figure out the best practices, also I would love to learn some basic animations

### Useful resources

I have a good knowledge in both HTML & CSS therefore I didn't need google

## Author

- Frontend Mentor - [@Aya333](https://www.frontendmentor.io/profile/Aya333)
