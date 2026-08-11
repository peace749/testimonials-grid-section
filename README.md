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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See a responsive testimonials layout across different screen sizes

### Screenshot

#### Mobile

![Testimonials Grid Section - Mobile](./screenshot-mobile.png)

#### Desktop

![Testimonials Grid Section - Desktop](./screenshot-desktop.png)

### Links

- Solution URL: https://github.com/peace749/testimonials-grid-section.git
- Live Site URL: [View the live site](YOUR_LIVE_SITE_URL)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS `clamp()`, `min()`, and relative units

### What I learned

This project helped me improve my understanding of responsive layouts and how to switch between Flexbox and CSS Grid depending on the screen size.

I used Flexbox for the mobile layout and CSS Grid for the desktop testimonial arrangement.

I also practiced using CSS functions such as `clamp()` and `min()` to make values more flexible across different screen sizes:

```css
.testimonials-grid {
  width: min(90%, 20rem);
}

```
I used `clamp()` for responsive spacing and sizing:

```css
.testimonial {
  padding: clamp(1.25rem, 2.5vw, 1.5rem);
}

```

Another thing I practiced was organizing colors with CSS custom properties:

```css
:root {
  --purple-50: hsl(260, 100%, 95%);
  --purple-300: hsl(264, 82%, 80%);
  --purple-500: hsl(263, 55%, 52%);
}
```

This made the stylesheet easier to maintain and helped me keep the colors consistent with the provided design.

### Continued development

I want to continue improving my responsive design skills, especially:

* Creating layouts that adapt smoothly between different screen sizes
* Using CSS Grid more confidently
* Improving my use of `clamp()`, `min()`, and other responsive CSS functions
* Writing cleaner and more maintainable CSS
* Building more Frontend Mentor projects to strengthen my frontend skills

### Useful resources

* [Frontend Mentor](https://www.frontendmentor.io) - Used for the challenge and design reference.
* [MDN Web Docs](https://developer.mozilla.org) - Useful reference for HTML and CSS concepts.

### AI Collaboration

I used AI as a learning and development assistant during this project to:

* Discuss the HTML structure before styling
* Understand which colors from the style guide belonged to different elements
* Review and improve my CSS
* Understand responsive breakpoints
* Compare Flexbox and CSS Grid approaches
* Improve responsive sizing with `clamp()` and `min()`
* Review my implementation and identify areas that could be improved

I wrote and implemented the project myself, using AI mainly for guidance, explanations, and reviewing my work.

## Author

- Frontend Mentor - [@peace749](https://www.frontendmentor.io/profile/peace749)
