# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)

  - [The challenge](#the-challenge)
  - [Links](#links)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Live Site URL: [Abiala-Israel-3-column-preview-card-component](https://3-column-abiala-israel.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Google Chrome Dev Tools

### What I learned

I learnt how to make the user to access the layout on a mobile screen. I had to search for materials on media queries which I studied thoroughly before applying in this project. Google Chrome developers tool also made things easier. Below is the snippet of the code for the media query.

@media (max-width: 375px) {
.main {
margin-top: 10px;
}
.container {
display: flex;
flex-direction: column;
overflow: scroll;
height: 1500px;
margin-top: 0px;
border-radius: 10px;
}
.box-1,
.box-2,
.box-3 {
width: 300px;
height: 500px;
}
}

### Continued development

In my future projects, I need to refine my strength on the media queries and learn more about css Grid.

### Useful resources

- [A Complete Guide to CSS Media Queries | CSS-Tricks](https://css.tricks.com/a-complete-guide-to-css-media-queries/) - This helped me in solving the media queries issues I encountered. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@Abiala705](https://www.frontendmentor.io/profile/Abiala705)
- Twitter - [@abiala_israel](https://www.twitter.com/abiala_israel)
