reponisve layout challenge 1

## Table of contents

- [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

It is to make the width of the into-content class half of the container class but you have to consider the text inside the intro-content shouldn't overflow at the bottom at small screen sizes.

### Screenshot

![](./screenshot.jpg)

file path for the screenshot:
screenshots/responsive layout challenge 1

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1, inorder to make the the width of the .intro-content half of the size of the container class we should use percentage value for the width of the intro-content class because if we use fixed value such as pixel, it will make the intro-content class to overflow it's parent once the our screen size become smaller than the width of the intro-content but percentage values will always make the the width of the container half of it's parent in every screen sizes.

2, inorder to stop text inside of the intro-content from overflowing at the bottom we shouldn't use the height property at the intro-content class and also for it's parent because at smaller screen sizes the width of the intro-content class and also our parent become smaller and the text inside intro-content class will shrink and increase it's height and if the our the container have fixed size height property it will make the bottom of our contanier will remain at the same position and the text inside will overflow it so, we shouldn't use height property. instead, we can use min-height if we want to set size for our container because our bottom of the container will adapt the height of the content inside it .

### Built with

- Semantic HTML5 markup
- CSS 3

### What I learned

this tutorial help me to understand about how you make websites responsive. before this challange I had done the social proof project in the frontend mentor and It wasn't responsive. after I take this first challange It had change my mindset on the responsiveness of website. websites are responsive by nature the problem is ourself who are making them not to be responsive. i start to fix the problem I had on the project by understaning the importance of using percentage value over other fixed size values and when to use the min-height property in this challenge.

### Continued development

i want to focus on flexbox , grid and responsive design.

## Author

- frontendmentor - [@aemrobe](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Aemro112](https://www.twitter.com/yourusername)
- freecodecamp - [@aemro11]
