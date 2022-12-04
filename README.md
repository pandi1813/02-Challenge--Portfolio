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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Creating a portfolio webpage using semantic HTML elements and to style it using CSS.
Page has to be responsive and adapt to various screen sizes
  

### Screenshot

![](./images/screenshot-1.PNG)
![](./images/screenshot-2.PNG)


### Links

- [Live Site URL](https://pandi1813.github.io/02-Challenge--Portfolio/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first design



### What I learned

Using variables instead of colour code in CSS

```css
:root {
  --dark-color: #280003;
  --light-color: #EEE0CB;
  --mid-color-1: #C2847A;
  --mid-color-2: #848586;
}
```

```css
header h1 {
  background-color: var(--dark-color);
  width: 100%;
  color: var(--light-color);
}
```

  Using CSS grid to set layout

```css
.project-examples {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2%;
  grid-template-areas: 
  "project-2 project-2"
  "project-1 project-3"
  "project-4 project-5";
}
```

### Continued development


I am going to focus more on simplifying HTML and CSS code to make it more organised and easier to read

### Useful resources

- [MDN website](https://developer.mozilla.org/en-US/docs/Web/CSS/grid) - I used it a lot when I couldn't remember ecactly how to do something 
- [W3Schools](https://www.w3schools.com/css/default.asp) - I did many of the excercises on this website before the bootcamp and they helped me a lot to learn how we can style with CSS


## Author
  Andrea Peter
- GitHub - [pandi1813](https://github.com/pandi1813)


