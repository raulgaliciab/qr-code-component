# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [GitHub](https://github.com/raulgaliciab/qr-code-component)
- Live Site URL: [Live](https://qr-code-component-iota-sand.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The first part was easy, having the basic HTML structure with all the elements in the correct order. After that, it was challenging to use the correct displays and properties. Always reminding that any minor change could break all the design.

One thing is learning the theory, and another very different is taking that theory to practice. Definitely an exercise that was worth it.

For example, I was stuck with the main element not using all the height space available. After investigating I learned that an element can only take the 100% of its parent. That way, the main element will only work like this:

```
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
}

main {
  display: flex;
  width: 100%;
  height: 100%;
  align-items: center;
  justify-content: center;
}
```

Also, having to consider not just the code itself, but the commits and documentation was very enriching.

### Continued development

One of the main areas I feel excited to keep practicing is CSS in general, specifically Responsive Design, the way the different displays works and the Box Model.

Also, I will keep working in the commit flow. Since this was a small project it was easy to keep everything in the main branch and a few commits. However, I know is not the best practice. Specially in larger projects.

## Author

- Raúl Galicia
- Frontend Mentor - [@raulgaliciab](https://www.frontendmentor.io/profile/raulgaliciab)
