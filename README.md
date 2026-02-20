# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). This project helped me strengthen my understanding of semantic HTML, CSS architecture, and responsive layout techniques using a mobile-first approach. 

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

- See hover and focus states for all interactive elements on the page

The goal of this challenge was to recreate a clean and minimal social profile card based on a provided design. The main focus was layout structure, visual accuracy, and interactive states.

### Screenshot

![](./assets/images/screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://victor-sc12.github.io/social-links-profile-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- BEM methodology for CSS naming
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Google Fonts

### What I learned

This challenge allowed me to reinforce several important frontend fundamentals.

- **Structuring semantic HTML**

  Instead of relying only on `<div>` elements, I used meaningful semantic tags like `<main>`, `<article>`, `<header>`, and `<nav>`. This improved the clarity and accessibility of the layout.

  ```html
  <main>
    <article class="social-prof-block">
      <header class="social-prof-block__header">
        ...
      </header>
      <p>...</p>
      <nav class="social-prof-block__nav">
        ...
      </nav>
    </article>
  </main>
  ```

  This helped me better understand how UI components can be structured more professionally.

  ---

- **Applying BEM for scalable CSS**

  I structured my CSS using a Block–Element–Modifier pattern:

  ```css
  .social-prof-block__paragraph--ubication {
    color: var(--green-hsl-color);
    font-weight: 600;
    margin-top: 1rem;
  }
  ```

  Using BEM made my styles more readable and organized. It also helped me clearly separate base styles from modifiers.

  ---

- **Using CSS variables for maintainability**

  I defined my color system inside `:root` using custom properties:

  ```css
  :root {
    --green-hsl-color: hsl(75, 94%, 57%);
    --white-hsl-color: hsl(0, 0%, 100%);
    --grey-700-hsl-color: hsl(0, 0%, 20%);
    --grey-800-hsl-color: hsl(0, 0%, 12%);
    --grey-900-hsl-color: hsl(0, 0%, 8%);
  }
  ```

  This made it easier to manage the design system and understand how scalable CSS architecture works.

  ---

- **Layout centering with Flexbox**

  I centered the card both vertically and horizontally using Flexbox on the `<body>`. This reinforced my understanding of alignment techniques in modern CSS.

### Continued development

Going forward, I want to:

- Improve accessibility by implementing better focus states.
- Practice more advanced responsive techniques.
- Refine my consistency when applying BEM modifiers.
- Continue improving spacing precision and visual balance.
- Each challenge helps me identify small details I can improve in the next one.

### Useful resources

- [BEM Info - BEM naming convention](https://en.bem.info/methodology/naming-convention/) - This official source on the BEM methodology helped me correctly define the names of the element classes using the naming convention.
- [MDN - Basic concepts of flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout/Basic_concepts) - This MND source served as a guide for me to define my flex layouts in the `<body>` and `<article>` elements that served as containers. 

### AI Collaboration

For this project, I used ChatGPT as a learning assistant.

I used it to:

- Clarify CSS concepts.
- Refine and professionalize this README.

AI was used as a support tool to reinforce learning, not to replace implementation. I wrote the code myself and used AI mainly for feedback and documentation improvement.

## Author

- **Name**: Víctor Suquilanda
- **Frontend Mentor** - [@victor-sc12](https://www.frontendmentor.io/profile/victor-sc12)
- **GitHub** - [@victor-sc12](https://github.com/victor-sc12)
