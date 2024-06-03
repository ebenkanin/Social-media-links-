# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents


  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: (https://github.com/ebenkanin/Social-media-links-)
- Live Site URL: (https://ebenkanin.github.io/Social-media-links-/)

## My process

### Built with

- Semantic HTML5 markup
- Vanilla CSS
- Flexbox


### What I learned

I was able to use media queries to make my work responsive. I also learned about the importance of ensuring you add the proper meta tags to your work to ensure the break points you want to define in your media queries actually work. 
I also found a way to focus on divs since they are by default not focusable.

```html
 <div class="wrapper">
            <div class="link-container" tabindex="0"><a href="#">Github</a></div>
            <div class="link-container"tabindex="0"><a href="#">Frontend Mentor</a></div>
            <div class="link-container"tabindex="0"><a href="#">LinkedIn</a></div>
            <div class="link-container"tabindex="0"><a href="#">Twitter</a></div>
            <div class="link-container"tabindex="0"><a href="#">Instagram</a></div>

        </div>
```
```css
.link-container:focus-within {
background-color: hsl(75, 94%, 57%);
color: black;
}

.link-container:focus-within a {
color: black;
}

## Author

-  [Eben Kanin]


