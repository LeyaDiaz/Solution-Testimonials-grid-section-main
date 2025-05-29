
# Frontend Mentor - Testimonials grid section solution

This is my solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot of my solution](./screenshots/127.0.0.1_5501_%20(1).png)

- Solution URL: [Solution-Testimonials-grid-section-main](https://github.com/LeyaDiaz/Solution-Testimonials-grid-section-main.git)
- Live Site URL: [Page-Solution-Testimonials-grid-section-main/](https://LeyaDiaz.github.io/Page-Solution-Testimonials-grid-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- **CSS Grid** (main layout)
- Flexbox (for some inner alignment)
- Mobile-first workflow

### What I learned

The biggest challenge for me in this project was using **CSS Grid** in a real-world scenario. Although I had practiced Grid before, this was the first time I applied it to a project with a complex, non-standard layout. It took several iterations to understand how to make the grid adapt responsively and how to position each card exactly as in the design.

Here's a snippet of the CSS Grid setup that made everything click for me:

```css
.box {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  grid-template-rows: auto;
  gap: 1rem;
}
.card-1 {
  grid-column: 1 / span 3;
}
.card-5 {
  grid-row: 1 / span 2;
  grid-column: 5;
}
```

I really enjoyed the challenge and now feel much more confident using CSS Grid for advanced layouts!

### Continued development

I want to keep improving my skills with CSS Grid, especially for even more complex layouts and responsive designs. I also plan to explore combining Grid and Flexbox more effectively, and to experiment with CSS Grid's `auto-fit` and `minmax` for fluid layouts.

### Useful resources

- [MDN Web Docs - CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - My go-to reference for understanding grid properties and alignment.
- [CSS-Tricks - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Helped me visualize how grid areas and lines work.
- [Frontend Mentor Discord Community](https://discord.gg/frontendmentor) - Great for getting feedback and support.

## Author

- Frontend Mentor - [@LeyaDiaz](https://www.frontendmentor.io/profile/LeyaDiaz)

## Acknowledgments

Thanks to the Frontend Mentor community for the helpful feedback and to everyone who shares their solutions and tips. This project was a lot of fun and a great learning experience!
