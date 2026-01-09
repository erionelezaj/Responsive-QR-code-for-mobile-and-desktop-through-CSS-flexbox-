# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I started by using a semantic article tag to structure the card instead of just using divs. I used CSS flexbox on the body to center the card perfectly and set a max width so it stays responsive on both mobile and desktop. By applying the box model I managed the padding and margins to create the right spacing and kept the image scaled correctly inside the container.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
### What I learned

Well the main thing that I was able to learn here is wrapping content in a div, while making sure the image fits perfectly within the article container that I added.

```html
<div class="container">
      <article class ="qrcodecard">
        <img src="images/image-qr-code.png" alt="qrcodecard">
        <h1>Improve your front-end skills by building projects</h1>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>

      </article>
```
```css
.qrcodecard img {
    display: block;
    width: 100%;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.05);
}

```




## Author

- Frontend Mentor - [@erionelezaj](https://www.frontendmentor.io/profile/erionelezaj)

