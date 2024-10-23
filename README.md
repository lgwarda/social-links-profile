# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [solution URL](https://github.com/lgwarda/social-links-profile.git)
- Live Site URL: [live site URL](https://lgwarda.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned the importance of using semantic HTML elements like `<article>`, `<header>`,`<footer>` and `<nav>`. This enhances the structure of my document, improves accessibility, and helps search engines understand the content better.

```html
<article>
  <header>
    <h1>Jessica Randall</h1>
    <p>London, United Kingdom</p>
  </header>
  <footer>
    <nav aria-label="Social Media Links">
      <ul>
        <li><a href="...">GitHub</a></li>
        <li><a href="...">LinkedIn</a></li>
      </ul>
    </nav>
  </footer>
</article>
```

I learned how the title attribute can enhance links by providing additional context. This small detail improves user experience by informing users about the link’s purpose before they click.

```html
<a
  href="https://github.com/jessicarandall"
  title="Visit Jessica's GitHub profile."
  >GitHub</a
>
```

I learned how to use @font-face to load custom fonts, providing greater flexibility in typography design. This allows me to maintain brand consistency and create a visually appealing design.

```css
@font-face {
  font-family: "Inter";
  src: url("./assets/fonts/static/Inter-Regular.ttf") format("truetype");
  font-weight: 400;
  font-style: normal;
}
```

### Continued development

### Areas for Continued Focus in Future Projects

1. **Advanced CSS Techniques**:

   - **Grid and Flexbox Layouts**: While I have a basic understanding, I want to dive deeper into using CSS Grid and Flexbox to create more complex layouts. Mastering these will allow me to design more responsive and visually appealing interfaces.
   - **Code Practice**: I plan to create layout challenges focusing on specific use cases, like card layouts or responsive navigation menus.

2. **Accessibility Best Practices**:

   - **ARIA Roles and Attributes**: I aim to learn more about ARIA roles and how to implement them effectively to enhance accessibility. Understanding how to make components like sliders, accordions, and modal dialogs accessible is a priority.
   - **Code Practice**: Conducting accessibility audits on my projects and using tools like Lighthouse to identify and fix issues.

3. **Performance Optimization**:
   - **Loading Fonts and Images Efficiently**: I want to explore best practices for optimizing font loading and image handling to improve page load times. Techniques like lazy loading and using responsive images can enhance performance.
   - **Code Practice**: Experimenting with different loading strategies and measuring their impact on performance.

### Conclusion

Focusing on these areas will significantly enhance my skills as a web developer, enabling me to create more sophisticated, user-friendly, and maintainable projects. By continuing to practice and refine these concepts, I aim to build a solid foundation for future endeavors in web development.

This ongoing commitment to learning will not only improve my technical abilities but also enhance my problem-solving skills, allowing me to tackle more complex challenges and contribute effectively to collaborative projects. Embracing these learning opportunities will ultimately lead to better user experiences and more successful outcomes in my work.

## Author

- Frontend Mentor - [@lgwarda](https://www.frontendmentor.io/profile/yourusername)
