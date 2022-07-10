# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Solution URL: [https://github.com/mei-e/product_preview_card]
- Live Site URL: [https://mei-e.github.io/product_preview_card/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I gained knowledge about Semantic HTML5 markup since I have learned so far in school is Basic HTML. I am also able to apply the concept of flexbox in this project, which is useful for developing responsive designs.

I also included a simple animation for the preview card and a transition for the button to add visual interest in this project.

```css
previewcard {
    display: flex;
    flex-direction: row;
    align-items: stretch;
    margin: 0;
    max-height:500px;
    max-width:60%;
    overflow:hidden;
    border-radius: 10px;
    animation: fadeEffect 0.5s;
}

@keyframes fadeEffect {
    from {
        opacity: 0;
        transform: translateY(-10px);
    }

    to {
        opacity: 1;
        transform: translateY(0px);
    }
}

button {
    font: 1rem 'Montserrat', sans-serif;
    background-color: var(--color-green-1);
    color: white;
    width: 300px;
    padding: 1rem;
    border: none;
    border-radius: 5px;
    text-align: center;
    cursor: pointer;
    transition: background 0.3s ease-in-out;
}

    button:hover {
        background-color: var(--color-green-2);
    }
```

### Continued development

As my knowledge is still limited to basic HTML and CSS, I have not used any frameworks that can be applicable for this project. 

Additionally, even though I am able to conduct a responsive web design, I have difficulty in wrapping the text as I resize the window.


### Useful resources

- [Resource 1](https://www.w3schools.com/) - This is a useful website as I can access almost all concepts of HTML and CSS that I need for this project.

## Author

- Frontend Mentor - [@mei-e](https://www.frontendmentor.io/profile/mei-e)
