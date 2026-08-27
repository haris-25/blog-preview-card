# Frontend Mentor - Blog Preview Card Solution

This is a solution to the Blog preview card challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The Challenge

Users should be able to:

- See a distinct hard-shadow card layout with responsive spacing
- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive title/tag elements

### Links

- **Live Site URL:** [https://blogg-previeww-cardd.netlify.app/](https://blogg-previeww-cardd.netlify.app/)
- **Solution URL:** [https://github.com/haris-25/blog-preview-card](https://github.com/haris-25/blog-preview-card)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom styling & reset (`box-sizing: border-box`)
- CSS Flexbox (vertical content stacking and author avatar row)
- Hard offset `box-shadow` for neo-brutalist card styling
- Viewport-relative sizing units (`vw`) for responsive scaling
- Media queries for mobile viewport adjustments

### What I Learned

This challenge provided hands-on practice with vertical space distribution and neo-brutalist styling:

* Implementing a solid offset drop shadow:
```css
#card {
  border: 1.5px solid black;
  border-radius: 12px;
  box-shadow: 10px 10px hsl(0, 0%, 7%);
}
```
Distributing spaced elements cleanly inside a fixed-height container:
```css
#content {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
```
Aligning author avatar and text seamlessly using Flexbox and column gaps:
```css
#img {
  display: flex;
  align-items: center;
  column-gap: 0.5vw;
}
```
