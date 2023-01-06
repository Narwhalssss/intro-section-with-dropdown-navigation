# Quiz 2 - Intro section page with interactive dropdown menu solution

This is a solution to the [Intro section page with interactive dropdown menu Quiz 2 challenge]

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![the website](site.png)



### Links

- Solution URL: [URL](https://github.com/Narwhalssss/intro-section-with-dropdown-navigation/blob/main/README.md)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

## Built with

-HTML

-CSS Flexbox

-CSS Grid

-Javascript


### What I learned



```html
<picture></picture>
```

```js
const menu = document.querySelector('.menu');
const dropdown = document.querySelectorAll('.dropdown');

menu.addEventListener('click',function(){
    menu.parentElement.classList.toggle('open');
    document.body.classList.toggle('nav-open');
})
dropdown.forEach(function(item){
    item.addEventListener('click',function(){
        item.parentElement.classList.toggle('link-open');
    })
})
```

## Your Detail 

- FullName - Mohammad Sulthan Azka
- StudentID - 2602209601
- BINUS Email - mohammad.azka@binus.ac.id



## Acknowledgments

I would like to thank Kenneth Lay, Davin Neilson, and Felix for helping me work on the line of codes, spotting/helping me find wrong syntaxes, and acompanying me.
