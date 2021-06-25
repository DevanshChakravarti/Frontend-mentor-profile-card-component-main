# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Challenge was to develop given layout in give viewport:

- Mobile-view (375px)
- Desktop-view (1440px)

### Screenshot

![Desktop-view of design](./images/desktop-view.png)

![mobile-view of design](./images/mobile-view.png)

### Links

- Solution URL: [profile-card codes](https://github.com/DevanshChakravarti/Fontend-mentor-stats-preview-card)
- Live Site URL: [profile-card live site](https://devanshchakravarti.github.io/Fontend-mentor-stats-preview-card/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Get to know more about background property how effeciently we can use it

For Desktop-view

```css
body {
  background: url("./images/bg-pattern-top.svg") -63% 255%, url("./images/bg-pattern-bottom.svg") 152% -220%,  var(--primary-dark-cyan);
}
```

For mobile-view

```css
body{
  background: url("./images/bg-pattern-top.svg") 130% 255% no-repeat, url("./images/bg-pattern-bottom.svg") -20% -205% no-repeat,  var(--primary-dark-cyan);    
}
```

### Continued development

Will use background property like wise I have used here and also going learn about it.

## Author

- GitHub - [Devansh Chakravarti](https://github.com/DevanshChakravarti)
- Frontend Mentor - [@Devansh](https://www.frontendmentor.io/profile/DevanshChakravarti)
