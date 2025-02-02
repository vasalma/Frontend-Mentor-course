# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 


## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Screenshot

[Take a look!](my-result.png)

## Built with

- Semantic HTML5 markup
- Flexbox
- [Font 'Outfit'](https://fonts.google.com/specimen/Outfit) - For font style


## What I learned

While working on this project, I gained hands-on experience with **Flexbox** and its related properties. Below are some of my major learnings, along with a code snippet demonstrating their usage: 
- Using `display: flex` to center content.
- Aligning items using justify-content and align-items.
- The Importance of `box-sizing: border-box.`

```css
* {
    box-sizing: border-box; /* Ensures that padding and borders do not affect the total width of elements */
}

body {
    display: flex;
    justify-content: center;  /* Centers content horizontally */
    align-items: center;      /* Centers content vertically */
    height: 100vh;            
    background-color: hsl(212, 45%, 89%);
    text-align: center;
}
```

### Continued development

I aim to improve my understanding of when to use different **units** (`px`, `%`, `vh`, `vw`, `em`, `rem`) to achieve better responsiveness and layout control. Key aspects I want to focus on:  

- The difference between **relative (`%`, `vw`, `vh`)** and **absolute (`px`)** units.  
- When to use `auto` vs. explicit values for **width** and **height**.  
- Best practices for **margin and padding** to ensure spacing is consistent across devices.  

On the other hand, I want to master more Flexbox Properties, including the ones that I used during this project; again, for better layout control, appearence and performance in general.

## Author

- Github - [Valeria Salgado](https://github.com/vasalma)
- Frontend Mentor - [@vasalma](https://www.frontendmentor.io/profile/vasalma)


