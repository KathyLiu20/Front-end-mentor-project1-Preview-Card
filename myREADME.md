# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

**NOT successfully implemented!!!!! NOT RESPONSIVE when shrinking the size, and desktop size is not fixedd to 1440px, and smartphone size is not fixed to 275px!!!! The position of the image and text are also messy when shrinking to smaller screen size.**

### Screenshot

![image-20210712063303513](C:\Users\Kathy Liu\AppData\Roaming\Typora\typora-user-images\image-20210712063303513.png)

![image-20210712064747473](C:\Users\Kathy Liu\AppData\Roaming\Typora\typora-user-images\image-20210712064747473.png)

If not change the positions (to relative) -> img then texts (img on left, texts on right...) -> responsive well. BUT how to change the text align and margins when changing to smaller screen??? 

### Links

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- bootstrap

### What I learned

1. add color filter to an img

```css
.img {
    filter: grayscale(100%) brightness(40%) sepia(100%) hue-rotate(-130deg) saturate(600%) contrast(0.8);
}
```
2. practiced positioning and margin, paddings.

``` css
position: relative;
left: 40%;
margin: top right bottom left;
margin: top left&right bottom;
margin: top&bottom left&right;
```

### Continued development

- Focus on RESPONSIVE webpage!

### Useful resources

- 

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername]

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**