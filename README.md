# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

### Screenshot

#### Desktop
![Desktop](./screenshots/desktop.png)

#### Tablet
![Tablet](./screenshots/tablet.png)

#### Mobile
![Mobile](./screenshots/mobile.png)


### Links

- Solution URL: [My solution URL](https://github.com/jannatulmitu03/huddle-landing-page)
- Live Site URL: [My live site URL](https://jannatulmitu03.github.io/huddle-landing-page)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Pseudo element
- Transform (transition)
- Desktop-first workflow

### What I learned

#### CSS
#### Pseudo element
```css 

.icons a i{
    font-size: 1.8rem;
    color: white;
    position: relative;
    transition: all .3s ease;
}

.icons a {
margin-left: 3rem;
}

.icons a i::after{
content: "";
height: 35px;
width: 35px;
position: absolute;
left: -9px;
bottom: -9px;
border-radius: 50%;
border: 1px solid white;
transition: all .3s ease;
}
```

#### Transform (transition)
```css 
.btn:hover{
    box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
    background-color:var(--Soft-Magenta);
    color: white;
    transition: all .3s ease;
}

```

## Author

- Website - [Jannatul Mitu](https://www.linkedin.com/in/jannatulmitu03)
- Frontend Mentor - [@jannatulmitu03](https://www.frontendmentor.io/profile/jannatulmitu03)
- Twitter - [@jannatulmitu03](https://twitter.com/jannatulmitu03)
