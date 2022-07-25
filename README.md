# Frontend Mentor - Product preview card component solution

This is a solution to the [https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa]. Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![images./screenshot.jpg]


### Links

- Solution URL: [https://github.com/Wahomethegeek/Product-preview-card.git]
- Live Site URL: [https://product-preview-card-umber.vercel.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I learned how to style a div class inside another div 
How to use css flexbox


```html
<div class="product_details">
        <p class="title">PERFUME</p>
        <h2>Gabrielle Essence Eau De Parfum</h2>
        <p class="description"> A floral, solar and voluptuous interpretation composed by Olivier
          Polge,Perfumer-Creator for the House of CHANEL</p>
          <div class="product_price">
            <ul>
            <li>$149.99</li>
            <li><s>$169.99</s></li>
            </ul>
          </div>
          <div>
```
```css
.product_price ul{
    display: flex;
    align-items: center;
    list-style-type: none;
    justify-content: left;
    margin: 1rem .8rem;

}
```

### Continued development

css grid
flexbox

### Useful resources

- [https://www.w3schools.com/css/tryit.asp?filename=trycss3_flexbox] -This helped me to style the div in flex.

## Author

- Website - [(https://www.yourhttps://wahomethegeek.github.io/wahome.github.io/-site.com]
- Frontend Mentor - [www.frontendmentor.io/Wahomethegeek]
- Twitter - [https://twitter.com/_Wahomekelvin]
