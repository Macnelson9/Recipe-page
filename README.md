# Recipe-page

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This is my shot at this challenge with same name from Frontend Mentor. The challenge is to builde a responsive recipe card page with an image at the top and the reciper following below. It aims to get users familiar with semantic HTML and CSS styling. So feel free to reuse this for your personal projects.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started out by observing the challenge page before attempting it. I then proceeded to writing the HTML involved to make the solution a success. I resolved to using the CSS Flexbox technique to achieve this solution. I used this technique to ensure that the contents of the page always remain at the center of the page. Then, I proceeded to making the container of the items a display:flex thereby, making the contents inside of it flex items. This more like a case of nested flex items. Well, that sums up evrything I did to achieve this solution. I also made use of CSS grid to get the footer part of the card to sit well together with the horizontal rulers.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

1. I learnt that one can use a grid inside of a flex container.
2. I learnt how to ensure that an image maintains its 100% width while sitting pretty inside of its parent container.

I'm proud of the following code snippets because I was having a hard time implementing the CSS grid in a previous challenge:

```html
<div class="footer">
  <p>Calories</p>

  <span>277kcal</span>
  <hr />
  <p>Carbs</p>

  <span>0g</span>
  <hr />
  <p>Protein</p>

  <span>20g</span>
  <hr />
  <p>Fat</p>

  <span>22g</span>
</div>
```

```css
.footer {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-template-rows: repeat(6, 1fr);
  justify-content: center;
  align-items: center;
}
.footer p {
  font-weight: 600;
  padding-left: 30px;
  padding-top: 5px;
  padding-bottom: 5px;
}

.footer span {
  grid-column: 4 / span 1;
  color: var(--nutmeg);
  font-weight: 700;
}

.footer hr {
  grid-column: 1 / -1;
  height: 0px;
  color: var(--light-grey);
}
```

### Continued development

Well, the only area tha I want to continue to improve on is implementing the CSS grid technique but I'm sure with enough practice I should be good soon.

## Author

- Facebook - [Uche Michael]
- LinkedIn - (https://www.linkedin.com/in/uche-ofatu)
- Frontend Mentor - [@macnelson9](https://www.frontendmentor.io/profile/Macnelson9)
- Twitter - [@macnelson92](https://www.x.com/macnelson92)

## Acknowledgments

I want to acknowledge the creator for my journey so far. My family too and a friend I met on frontend mentor by name of Alex. Thank you for the tips man.

