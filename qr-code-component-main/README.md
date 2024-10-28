# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Links

- My LinkedIn: https://www.linkedin.com/in/f-h-touré 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned that when flex items are not centering it's probably due to the page dimensions. 

```css
body {
    ...
    height: 100vh; 
    margin: 0; /*removes scrollbar*/
}
```
Without these two lines, the content is not at the center of the page and a right scrollbar appears.

Also, I tried using some media query for responsiveness but I deemed it unecessary since it the doesn't really change the page in mobile dimesions. When I tried implementing it, it didn't work at first and I learned that it was because you are suppose to write media queries at the bottom of the CSS file (for it to not overlap with the rest of the styling).

### Continued development

I will probably use this page to implement fun and interesting things I learn in web development. Next step will probably be to add some JavaScript.

### Useful resources

- [ChatGPT](https://www.chatgpt.com) - Helped me figure out why the container was not centering in the body (turned out it was because of the height) and why my attempted media query was not working.

## Author

- Frontend Mentor - [@faetem](https://www.frontendmentor.io/profile/faetem)

## Acknowledgments

Thanks P.G. for watching me build this on a video call although you didn't understand much about what was going on... :sob::pray:

