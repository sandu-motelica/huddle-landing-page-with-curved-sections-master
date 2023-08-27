# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

./Screenshot.png

### Links

- Solution URL: https://github.com/sandu-motelica/huddle-landing-page-with-curved-sections-master.git
- Live Site URL: https://sandu-motelica.github.io/huddle-landing-page-with-curved-sections-master/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

With Flexbox, arranging elements within containers became a breeze. It made alignment and distribution a snap, adapting seamlessly to different screens. CSS Grid introduced me to two-dimensional layout control, making complex grid creation and responsiveness a cinch. And then there was background positioning — a simple yet impactful technique. By combining background images with precise positioning, I learned to create parallax effects, add visual interest, and enhance overall aesthetics.

.bg {
background-size: 100%;
background-repeat: no-repeat;
width: 100%;
height: 22.4rem;
}

.bg-top {
background-position: bottom;
}
.bg-bottom {
background-position: top;
}

.section-1-top {
background-image: url(../images/bg-section-top-desktop-1.svg);
}
.section-1-bottom {
background-image: url(../images/bg-section-bottom-desktop-1.svg);
}

.section-2-top {
background-image: url(../images/bg-section-top-desktop-2.svg);
}
.section-2-bottom {
background-image: url(../images/bg-section-bottom-desktop-2.svg);
}
.footer-top {
background-image: url(../images/bg-footer-top-desktop.svg);
}

## Author

- Frontend Mentor - [@sandu-motelica](https://www.frontendmentor.io/profile/sandu-motelica)
- GitHub - [@sandu-motelica](https://github.com/sandu-motelica)
