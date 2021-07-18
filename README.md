# Side Hustle Internship 3.0

## Project: Frontend Mentor - Fylo dark theme landing page solution

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

- Mobile View
  ![](./design/mobile-design.jpg)

- Desktop View
  ![](./design/desktop-design.jpg)

### Links

- Solution URL: [Github](https://github.com/Uzenedo/fylo-dark-theme-landing-page)
- Live Site URL: [Live Host]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned a new concept called css grid areas. It is a very powerfull feature for layout arrangements to achieve responsive designs.

Below is an example of code snippets for css grid:

```html
<section class="contact-info">
  <div class="contact-info-logo">
    <a href="#">
      <img src="./images/logo.svg" alt="logo" />
    </a>
  </div>
  <div class="contact-info-location">
    <div class="contact-info-location-item">
      <img
        class="img-footer"
        src="./images/icon-location.svg"
        alt="icon-location"
      />
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua
      </p>
    </div>
  </div>
  <div class="contact-info-contacts">
    <div class="contact-info-contacts-item">
      <img class="img-footer" src="./images/icon-phone.svg" alt="icon-phone" />
      <p>+1-543-123-4567</p>
    </div>
    <div class="contact-info-contacts-item ">
      <img class="img-footer" src="./images/icon-email.svg" alt="icon-email" />
      <p>example@fylo.com</p>
    </div>
  </div>
  <nav class="contact-info-links">
    <ul class="contact-info-links-list">
      <li><a href="#">About Us</a></li>
      <li><a href="#">Jobs</a></li>
      <li><a href="#">Press</a></li>
      <li><a href="#">Blog</a></li>
    </ul>
    <ul class="contact-info-links-list">
      <li><a href="#">Contact Us</a></li>
      <li><a href="#">Terms</a></li>
      <li><a href="#">Privacy</a></li>
    </ul>
  </nav>
</section>
```

```css
.contact-info {
  margin-top: 50px;
  padding: var(--padding-footer);
  display: grid;
  background-color: var(--dark-blue-3);
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(2, auto);
  grid-template-areas:
    "logo logo logo logo"
    "location contacts links social"
    "attribution attribution attribution attribution";
}

.contact-info-logo {
  grid-area: logo;
}

.contact-info-location {
  grid-area: location;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

I would continue to improve myself in the following areas: css flexbox, grid, colors, and fonts selection.

### Useful resources

- [StackOverFlow](https://stackoverflow.com/questions/47587892/how-does-css-grid-layout-works) and
- [Wesbos](https://cssgrid.io/)- These resources helped me to understand the fundamentals of css grid and its powerful features for responsive designs. I really liked CSS Grid and will use it going forward.
- [StackOverFlow](https://stackoverflow.com/questions/44623821/how-to-use-flexbox) - It helped me to understand flexbox principles. I would recommend it for anyone learning flexbox for the first time.
- [CSS Tricks](https://css-tricks.com/the-many-ways-to-change-an-svg-fill-on-hover-and-when-to-use-them/) - This is an amazing article which helped me finally understand how to use CSS Filter on SVG when using hover effect. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@Uzenedo](https://www.frontendmentor.io/profile/Uzenedo)
- Github - [Uzenedo](https://github.com/Uzenedo/)

## Acknowledgments

**My acknowledgement goes to all the open source communities who have shared their knowledge in different aspects of web development.**