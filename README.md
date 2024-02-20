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
    - [Useful resources](#useful-resources)
  - [Author](#author)


## Overview

### Screenshot

![My project screenshot](/project-screenshot.png)


### Links

- Solution URL: [GitHub](https://github.com/robynainsley21/qr-code-component-main.git)
- Live Site URL: [Netlify](https://dulcet-paprenjak-9084f2.netlify.app/)

## My process

### Built with

- CSS custom properties
- Flexbox


### What I learned

What I've learned was that using flexbox alone to center an item on a page does not always work. A simple line of code that I found on [Stack Overflow](https://stackoverflow.com/questions/31217268/center-div-on-the-middle-of-screen) helped with this. By making the parent container 100vh, the child item was centered.

See last line of code snippet below:


```css
#card_container {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  height: 100vh;
}
```


### Continued development

Unrelated to the project, CSS Grid is something I would like to master. It tends to get tricky with the 'span' property and media queries.


### Useful resources

- [Stack Overflow](https://stackoverflow.com/) - This site is helpful at times as it is a platform for developers to come together and help find a solution, especially those with similar coding problems.
- [W3Schools](https://www.w3schools.com/) - This site offers basic understanding of elements and their uses.


## Author

- Frontend Mentor - [@robynainsley21](https://www.frontendmentor.io/profile/robynainsley21)




