# Frontend Mentor - Huddle landing page with a single introductory section

This is a solution to the [Huddle landing page with a single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Lessons learned](#lessons-learned)
  - [Built with](#built-with)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size

### Screenshot

![app screenshot](./screenshot.png)

### Links

- Live Site URL: [Live Site on Netlify](https://modest-thompson-63a5f2.netlify.app)

## My process

### Lessons learned

I ran into a lot of issues with using SVGs in the CSS. No matter what I tried they wouldn't display. It turns out that the plugin I was using in Parcel to make an SVG sprite was incompatible with using svgs as background images in CSS. It works fine for SVGs in the html, but not in CSS. Lesson learned: Keep the build **simple**.

### Built with

- Semantic HTML5 markup
- Mobile-first workflow
- SCSS

## Author

- Website - [Travis Ricks](http://travisricks.com/)
- Frontend Mentor - [@travisricks](https://www.frontendmentor.io/profile/travisricks)
- Twitter - [@itsTravisRicks](https://twitter.com/itsTravisRicks)
