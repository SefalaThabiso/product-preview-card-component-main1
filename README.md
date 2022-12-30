# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![](./images/Screenshot%202022-12-30%20at%2020-41-20%20Frontend%20Mentor%20Product%20preview%20card%20component.png)
![](./images/Screenshot%202022-12-30%20at%2020-44-52%20Frontend%20Mentor%20Product%20preview%20card%20component.png)




### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learn to use html <source> to replace images at a certain width



To see how you can add code snippets, see below:

```html
        <picture class="product__img">
          <source
            srcset="./images/image-product-desktop.jpg"
            media="(min-width: 460px)"
          />
          <img
            src="./images/image-product-mobile.jpg"
            alt="Picture of a perfume bottle laying on it's side"
          />
        </picture>
```
Also to hide elemnts while making them visible to screen readers

```html
 <p class="product__original__price">
              <span class="visually-hidden">Current price:</span>
              <s>$169.99</s>
            </p>

```
```css
  /* ie9+ */
.visually-hidden:not(:focus):not(:active) {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}


```


### Continued development

Im still not great with grid. I need to improve using it. I also still feel like an impster so i need to feel more confident with coding.

my biggest drawback is completing a project by myself without comsulting youtube tutorials. I hope to gain the experience nessesary to work on a project by myself.



### Useful resources

- [Example resource 1](https://www.joshwcomeau.com/css/custom-css-reset/) - This helped me to reset my elements



## Author

- Website - [Thabiso](https://www.your-site.com)
- Frontend Mentor - [@SefalaThabiso](https://www.frontendmentor.io/profile/SefalaThabiso)



## Acknowledgments

I would like to thank kevin powell for great youtube tutorials and everyone who commented on my solutions. Learning alone is hard but having a community which support you is great