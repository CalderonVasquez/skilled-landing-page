# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/image/SS-%20Skilled%20e-learning%20landing%20page.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS
- CSS Grid

### What I learned

I had issues with the hero image so I asked Chat-GPT and this code fixed my issues.

```css
.overflow-wrapper {
    overflow-x: hidden;
    position: relative;
}
```

serves two main purposes when dealing with a hero image that has negative margins:

1. **Prevents Horizontal Scrollbars**: By setting `overflow-x: hidden`, it hides any horizontal overflow content that might otherwise extend beyond the viewport. Negative margins on the hero image can push content outside the normal bounds of the page, which could cause unwanted horizontal scrollbars. This rule ensures that any content extending outside the viewport horizontally is clipped, avoiding those scrollbars.

2. **Maintains Positioning Context**: By setting `position: relative`, you ensure that the `.overflow-wrapper` creates a new containing block for absolutely positioned elements inside it (such as the hero image, if needed). This keeps the positioning of child elements relative to this wrapper, which helps prevent layout shifts or unexpected behavior caused by the negative margins of the hero image.

Together, these properties ensure that the layout remains visually contained without any unwanted overflow or positioning issues, making the design more robust and clean.

## Author

- Frontend Mentor - [@CalderonVasquez](https://www.frontendmentor.io/profile/CalderonVasquez)
