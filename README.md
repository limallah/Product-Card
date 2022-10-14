# Product preview card component solution

This is a solution to the [Product preview card component challenge.

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
- See hover and focus states for interactive elements

### Screenshot

![C:\Users\User\Desktop\Donald Ass\Screenshot 2022-10-14 at 05-42-04 PERFUME.jpg]

### Links

- Solution URL: (C:\Users\User\Desktop\Donald Ass)
- Live Site URL: (file:///C:/Users/User/Desktop/Donald%20Ass/perfume.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid



### What I learned

I learnt the difference between a "span tag" and "div tag", div tag simply means a block of text or sentence while span tag is a continueous text or sentence. I have also learnt how to exclude an element from inheriting a particular style. 

```html
html tag I found intresting from this challenge.
<p>$149.99 &nbsp;&nbsp;&nbsp;<span>$169.99</span></p> 
```
```css
css tag I found intresting from this challenge.
.price span{
    font-family: 'Montserrat', sans-serif;
    font-size: 0.5em;
    font-style: italic;
    color: hsl(228, 12%, 48%);
    text-decoration:line-through;
}

.price > :not(span) {
    font-family: 'Montserrat', sans-serif;
    font-style: italic;
    color: hsl(158, 36%, 37%);
    font-size: 1.8em;
    text-indent: 15px;
}
```

### Continued development

Some part of css I will want to focus on to improve my understanding in the future are:
- css grid
- css flexbox and model
- css positioning and float

### Useful resources

- [Example resource 1](https://www.w3schools.com/css/css_grid.asp) - This has really helped me in understanding vertical and horisontal grids which forms rows and colume. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.rithmschool.com/courses/html-css-fundamentals/positioning) - This is an amazing article which helped me to understand positioning and float. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Halima Ibrahim](https://www.halib.me)

- Twitter - [@Limalla70](https://www.twitter.com/Limallah70)

## Acknowledgments

My acknowledgment gose to my beloved husband and my friend AY for sharing their ideas to the success of this challenge. Not to forget my wonderful mentors Sir Donald and Miss Phillia for giving us this opportunity to become successful in the path of Software Engineers.

