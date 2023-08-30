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
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Desktop Design](./design/desktop-design.jpg)
![Mobile Design](./design/mobile-design.jpg)

### Links

- Solution URL: [My solution](https://github.com/Nrupatungan/huddle-landing-page)
- Live Site URL: [Live site](https://nrupatungan.github.io/huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned


```css
:root{
    /* colors */
    --violet : hsl(257, 40%, 49%);
    --magenta : hsl(300, 69%, 71%);

    /* font family */
    --poppins: 'Poppins', sans-serif;
    --open-sans: 'Open Sans', sans-serif;

}

body{
        background: url(./images/bg-desktop.svg) no-repeat;
        background-size: cover;
        background-color: var(--violet);
        grid-template-areas: 
            "h . ."
            "m m m"
            ". . f";
    }

header{
  grid-area: h;
}

main{
  grid-area: m;
}

footer{
  grid-area: f;
}

```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

## Author

- Frontend Mentor - [@Dinesh_Sake](https://www.frontendmentor.io/profile/Nrupatungan)
- Github - [@Dinesh_Sake](https://github.com/Nrupatungan)