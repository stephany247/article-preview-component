# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Screenshot

![](./images/Screenshot%202024-12-14%20at%2020-34-27%20Frontend%20Mentor%20Article%20preview%20component.png)
![](./images/Screenshot%202024-12-14%20at%2020-33-33%20Frontend%20Mentor%20Article%20preview%20component.png)

### Links

- Solution URL: [Article Preview Component solution](https://github.com/stephany247/article-preview-component)
- Live Site URL: [Article Preview component](https://stephany247.github.io/article-preview-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Tailwind CSS](https://tailwindcss.com/docs/installation) - For styles
- Javascript

### What I learned

Working through this project, I gained a deeper understanding of several key concepts and techniques that helped me improve my front-end skills. Here are some of the major takeaways:

1. Responsive Design with TailwindCSS: I became more comfortable using TailwindCSS to create responsive layouts. By using classes like sm:m-auto, sm:w-max, and sm:flex, I was able to ensure that the layout adjusted seamlessly on different screen sizes.

```html
<main
  class="bg-white mx-6 my-20 sm:m-auto rounded-xl shadow-lg sm:flex sm:flex-row max-w-screen-md sm:w-max"
></main>
```

2. Working with Images: I learned how to make images responsive by setting their width using TailwindCSS classes, such as w-full and sm:w-2/5, which ensures they scale properly on different screen sizes.

```html
<img class="w-full sm:w-2/5 rounded-t-xl sm:rounded-l-xl sm:rounded-tr-none h-auto"
```

3. Handling Interactive Elements with JavaScript: I implemented the functionality to toggle the visibility of the share links when the share button is clicked. This taught me how to manage DOM interactions with JavaScript effectively.

```js
const toggleVisibility = () => {
  shareContent.classList.toggle("hidden");
};

shareBtn.addEventListener("click", function () {
  toggleVisibility();
});
shareBtnClose.addEventListener("click", function () {
  toggleVisibility();
});
```

### Continued development

I plan to focus on gaining more experience with advanced JavaScript, particularly mastering concepts. Additionally, I want to deepen my understanding of JavaScript frameworks like React, including state management, hooks, and component lifecycle. This will help me build more dynamic and efficient applications in the future.

### Useful resources

- [Stack Overflow](https://stackoverflow.com/) - I found helpful solutions for CSS issues, like handling hover effects and box shadows, which were crucial for implementing the card design in this project.

## Author

- Website - [Onyinye Stephanie Oguocha](https://www.your-site.com)
- Frontend Mentor - [stephany247](https://www.frontendmentor.io/profile/stephany247)
- Twitter - [@stephanyoguocha](https://x.com/stephanyoguocha)

## Acknowledgments

I would like to give a big thanks to the Frontend Mentor community and the resources on Stack Overflow for helping me troubleshoot and improve my project.
