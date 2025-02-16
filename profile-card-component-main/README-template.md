# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Screenshot

[Take a look!](my-result.png)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/profile-card-website-XfyeX1QdN0)
- Live Site URL: (https://profile-card-byvasalma.vercel.app/)

## Built with

- Semantic HTML5 markup
- Flexbox
- [Font 'Kumbh Sans'](https://fonts.google.com/specimen/Kumbh+Sans) - For font style


## What I learned

While working on this project, I gained hands-on experience with **CSS positioning, Flexbox, and responsiveness**. Below are some of my major learnings, along with a code snippet demonstrating their usage:

- I learned how to use position: absolute and position: relative effectively to place elements correctly.
- I used display: flex to center content and align elements properly.
- By using z-index and positioning, I ensured that the profile picture remains on top without interfering with text.

```css
.profile-picture {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 4.5px solid white;
  position: absolute;
  top: 90px;
  left: 50%;
  transform: translateX(-50%);
  /* Since left: 50% places the element's left edge in the middle, we use transform: translateX(-50%) to move it back by 50% of its own width, effectively centering it. */
}

.profile-info {
    display: flex;
    flex-direction: column;
    align-items: center; /* Centers content horizontally because of column */
    justify-content: center; /* Centers content vertically because of column */
    padding: 20px;
}

.pattern-top {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 200px;
  background: url('pattern.svg') no-repeat center/cover;
  z-index: -1; /* Pushes it behind other elements */
}
```

### Continued development

I aim to improve my understanding of CSS positioning, z-index, and responsive design to achieve better layout control and ensure elements remain visually consistent across different screen sizes. Key aspects I want to focus on:

- The correct use of position: absolute vs. relative to avoid misalignment issues when resizing the screen.
- How to effectively use z-index to manage overlapping elements without interfering with the layout.
- 
Ensuring that elements like the profile picture remain fixed and do not shift unpredictably when changing dimensions.
On the other hand, I want to refine my Flexbox and responsiveness skills to create layouts that are more adaptable and visually appealing across different devices:

- Improving the use of justify-content and align-items for better alignment in various screen sizes.
- Learning when to use min-height vs. height to prevent elements from breaking on smaller screens.
- Ensuring background elements remain properly positioned without disrupting the layout when resizing the viewport.

## Author

- Github - [Valeria Salgado](https://github.com/vasalma)
- Frontend Mentor - [@vasalma](https://www.frontendmentor.io/profile/vasalma)
