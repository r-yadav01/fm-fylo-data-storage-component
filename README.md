# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). I build it using vanilla css, html and a little bit of js.

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

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Github](https://github.com/r-yadav01/fm-fylo-data-storage-component)
- Live Site URL: [Github pages](https://r-yadav01.github.io/fm-fylo-data-storage-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- I learned how to customize the `<input>` element of type="range". These has to be customized with different css selectors depending on the type of browser.

- This has 2 parts which can be selected as pseaudo-elements. After selecting we have to apply `appearance: none` to both parts to be able to customize them.

- There is the handle(thumb) after selecting this can be treated as normal span block and then there is the slider's background which can be styled by just using the `input[type="range"]` selectors background-color or background-image property.

- Modern css nesting is so cooool.

### Continued development

- I was not able to apply `overflow-x: hidden` on the `.pointer` selector, don't know why it did not worked.
- So I have to use a different way to point to the end of the input's range.

## Author

- GitHub - [r-yadav01](https://github.com/r-yadav01)
- Frontend Mentor - [@r-yadav01](https://www.frontendmentor.io/profile/r-yadav01)
- Twitter - [@r_yadav01](https://x.com/r_yadav01)
- Bluesky - [@r-yadav01.bsky.social](https://bsky.app/profile/r-yadav01.bsky.social)
