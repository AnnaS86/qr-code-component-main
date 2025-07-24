# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

It is a Mobile-first solution using CSS Flexbox

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/profile/AnnaS86)
- Live Site URL: [Github Pages](https://annas86.github.io/qr-code-component-main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

1. The page markup should be semantic, each block of the site should have a heading
   
2. The favicon file must be stored in the root of the project.

3. An element on a page can be hidden while still being accessible to a screen reader.

You can see my example below:

```html
<h1 class="visually-hidden">Frontend Mentor | QR code component</h1>
```
```css
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  border: 0;
  overflow: hidden;
  clip: rect(0 0 0 0);
  clip-path: inset(100%);
  white-space: nowrap;
}
```
4. Code blocks can be conveniently aligned using flexbox.

```html
<section class="card">
      <h2 class="visually-hidden">QR code component</h2 >
      <div class="card-image">
        <img class="image" src="./images/image-qr-code.png" alt="QR Code">
      </div>
      <div class="card-text">
        <h3 class="card-title">Improve your front-end skills by building projects</h3>
        <p class="paragraph">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
    </section>
```

```css
.card {
  display: flex;
  width: 320px;
  flex-direction: column;
  text-align: center;
  margin: 0 auto;
  padding: 16px 16px 40px; /* top, sides, bottom — как в макете */
  background-color: var(--color-card-bg);
  border-radius: 20px;
  box-shadow: var(--card-shadow);
}
```
5. You can connect the font like this

```css
@font-face {
  font-family: 'MyFont';
  src: url('../fonts/MyFont.woff2') format('woff2'),
       url('../fonts/MyFont.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
```

### Continued development

I want to continue focusing on new concepts in my future projects. 

I plan to learn how to use bem, CSS preprocessors, JavaScript, frameworks.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

## Author

- Frontend Mentor - [@AnnaS86](https://www.frontendmentor.io/profile/AnnaS86)
- All my solutions - [My solutions](https://www.frontendmentor.io/profile/AnnaS86/solutions)

## Acknowledgments

While working on the project, I used AI as my assistant.