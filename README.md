# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./design/desktop-1440px.png)
![](./design/desktop-1920px.png)

### Links

- Live Site URL: [https://rostyagai.github.io/profile-card-component-frontend-mentor/](https://rostyagai.github.io/profile-card-component-frontend-mentor/)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- CSS Flexbox
- CSS Position properties

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.
During this challenge i got my first expirience working with flexbox. Flexbox is awesome! I dont know why I haven't used it before. This challenge really showed me what i need to practice/learn more hardly. I think Im completed this challenge but
not to the end. My solution is works great on desktop, but on mobile i have some issues with it. It happened because of my not enough knowledge in responsive CSS, so after realising that im gonna work hard on it.

Here is some code snippets im insecure with:

```html
<body>
    <img src="images/bg-pattern-top.svg" alt="" class="pattern-top" />
    <img src="images/bg-pattern-bottom.svg" alt="" class="pattern-bottom" />
    <!-- <div class="wrapper"> -->
    <div class="card">
      <img src="images/bg-pattern-card.svg" alt="bg-pattern-card" class="card-pattern" />

      <div class="info-container">
        <img src="images/image-victor.jpg" alt="Victor-pfp" class="pfp" />
        <h1>Victor Crest</h1>
        <span class="card-age">26</span>
        <p class="card-city">London</p>
        <hr />
        <div class="stats-container">
          <div class="item">
            <span class="stats-num">80K</span>
            <p class="stats-name">Followers</p>
          </div>
          <div class="item">
            <span class="stats-num">803K</span>
            <p class="stats-name">Likes</p>
          </div>
          <div class="item">
            <span class="stats-num">1.4K</span>
            <p class="stats-name">Photos</p>
          </div>
        </div>
      </div>

      <!-- </div> -->

      <div class="attribution">
        Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. Coded by <a href="#">Alexander Rostyagai</a>.
      </div>
    </div>
  </body>
```

```css
.card {
  background-color: #fff;
  text-align: center;
  position: relative;
  width: 370px;
  height: 400px;
  border-radius: 18px;
  margin-bottom: 30px;
  box-shadow: 0px 0px 55px -35px;
}
.card-pattern {
  position: relative;
  display: block;
  width: 100%;
  border-radius: 18px 18px 0 0;
}
.info-container {
  position: relative;
  top: -50px;
}

.pattern-top {
  z-index: -1;
  position: absolute;
  top: -560px;
  left: -280px;
}
.pattern-bottom {
  z-index: -1;
  position: absolute;
  bottom: -560px;
  right: -280px;
}
```


### Continued development

Now im gonna dive into advanced flexbox, grids, semantic tags, z-index and other... After reaching enough level of knowledge of HTML5, CSS3 and JavaScript im planning to dive into tailwind CSS and react


### Useful resources

- [MDN - Box-shadows](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This helped me for understanding syntax of box-shadow. I really liked this property and will use it going forward.
- [w3schools](https://www.w3schools.com/howto/howto_css_style_hr.asp) - This is an amazing article which helped me finally understand **"hr"** styling. I'd recommend it to anyone still learning this concept.
- [SlayingTheDragon](https://www.youtube.com/watch?v=phWxA89Dy94) - GOAT guide into flexbox.


## Author

- Website - at moment i dont have any(((
- Frontend Mentor - [@Rostyagai](https://www.frontendmentor.io/profile/Rostyagai)


