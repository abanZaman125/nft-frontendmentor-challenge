# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).  

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Some pretty cool hover states

### What I learned

I totally forgot that pseudo-classes are just _states_ of their elements (thus, you can access their children):

```css
.icon-container.center:hover .eye-icon{
  filter: opacity(1);
}
```

### Problems I faced:

A problem I faced was how to code the hover state for the cube image.
It was easy to code the eye svg (just `absolute` position it and the parent div will center it).
For the background I tried changing the [color](https://www.delftstack.com/howto/css/css-change-image-color/) of the image but opted to just make a div on top of the image.

## Author
- Frontend Mentor - [@abanZaman125](https://www.frontendmentor.io/profile/abanZaman125)
