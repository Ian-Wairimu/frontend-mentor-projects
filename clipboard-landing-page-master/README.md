# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [Screenshot](#screenshots)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)

### Screenshots

Desktop Layout
![](./design/screenshot01-desktop.png)

Mobile Layout
![](./design/screenshot01-mobile.png)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/clipboard-landing-page-with-css-grid-and-flexbox-vebzO1g9zi)
- Live Site URL: (https://smgy94.github.io/front-end-mentor-projects/clipboard-landing-page-master/)

## My process

I opened the design in Adobe Photoshop and broke it into several different sections using yellow & blue rectangles. I looked at each section and then decided to use either CSS Grid / Flexbox to achieve the desired layout.

I began working from the top down. Once I completed a section on desktop I would then ensure that it was also working on Mobile using a media query.

![](./design/processes.png)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

1.  I an issue with chaning the colour of the social media icons (.SVG's) on :hover

The solution was to specify 'svg path'

```svg path:hover {
  fill: var(--Strong-Cyan);
}
```

2.  I had issues getting this to work on Tablet sized devices.

My solution was to add a media query for tablets:

@media only screen and (min-width: 481px) and (max-width: 820px) { }

3.  I wasn't sure if my HTML was completely semantically correct.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

I'm going to continue working with CSS Grid & Flexbox to build page layouts.
I'm also going to re-search how to use the CSS clamp() function. This will help text to scale better across multiple devices.

### Useful resources

- [A Complete Guide to Grid ](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me for laying out all of pages elements. I really liked this guide and will use it going forward.

## Author

- Frontend Mentor - [@Smgy94](https://www.frontendmentor.io/profile/Smgy94)
- LinkedIn - (https://www.linkedin.com/in/shanemcgeown/)
