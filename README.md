# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](ss.png)
![](ss-mobile.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- I used a grid layout, despite the overall banner being one dimensional, as using flexbox would entail sizing each of the child elements. Simpler the better.
- For the img-box container div there was an initial struggle to decide whether to apply the image as a background-image or to nest an image element.
  I went with the former because this for some reason made the image scale better when resizing the browser. In addition, I was already familiar with applying
  a transparent background over the image using linear-gradient which is for the mentioned property.
- Background images need a defined height if the situation calls for it, otherwise you will see nothing. This was evident when the banner was set to just a
  single column.

### Continued development

- Responsiveness with media queries
- Image Responsiveness

## Author

- Frontend Mentor - [@dagimchi](https://www.frontendmentor.io/profile/dagimchi)
- Twitter - [@dagimchi](https://www.twitter.com/dagimchi)
