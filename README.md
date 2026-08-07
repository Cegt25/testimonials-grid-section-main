# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](.images/screenshot.jpg)
![](.images/screenshot2.jpg)


### Links

- Solution URL: https://github.com/Cegt25/testimonials-grid-section-main
- Live Site URL: https://cegt25.github.io/testimonials-grid-section-main/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I used Flexbox for small screens and CSS Grid for large screens; I learned a bit more about them—I know I still have more to learn, but I am taking on challenges to further my progress.

```html
<article class="testimonial testimonial-2">
      <div class="user-info">
        <img src="./images/image-jonathan.jpg" alt="Jonathan Walters" class="avatar">
        <div class="user-info-text">
          <h2 class="name">Jonathan Walters</h2>
          <p class="status">Verified Graduate</p>
        </div>
      </div>

      <p class="lead">The team was very supportive and kept me motivated</p>

      <p class="comment">“ I started as a total newbie with virtually no coding skills. I now work as a mobile engineer
      for a big company. This was one of the best investments I’ve made in myself. ”</p>
    </article>
```
```css
.testimonial-2 {
    background-color: var(--grey-500);
    color: var(--white);
}
```

### Useful resources

- [color code](https://htmlcolorcodes.com/) - It really helped me establish the colors.


### AI Collaboration

- What tools did you use (Gemini)
- How did you use them (debugging, brainstorming solutions)

## Author

- Frontend Mentor - [@cegt25](https://www.frontendmentor.io/profile/Cegt25)
- Twitter - [@Cegt25](https://www.twitter.com/cegt25)
