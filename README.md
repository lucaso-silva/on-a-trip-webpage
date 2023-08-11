# On a Trip

![On-a-trip](https://github.com/lucaso-silva/on-a-trip-webpage/assets/97140968/d3556727-ed70-422c-b0c8-f5997cc24fba)
<p align="center"> See in the <a href="https://lucaso-silva.github.io/on-a-trip-webpage/"> link </a></p>

## Overview
On a Trip is an unreal Travel packages website developed as one of the criteria of evaluation on the course of Web Development I.
It was developed using HTML5 and CSS3. 

> Status: Concluded 
- Deadline: 08.02.23 ✅
---

### Objectives


## Built with
- Semantic HTML5 markup
- Mobile-first workflow
- CSS custom properties
- Fleexbox
- CSS-grid

## What I learned 💡
This project was helpful to consolidate my knowledge about HTML5 and CSS3. 

In the CSS file, I tried as much as possible to select the desired element using advanced selectors and pseudo-classes, which was one of the subjects studied during the discipline of Web Development I.

To animate the cards when the mouse is over them, I used the child combinator ``>`` associated with the pseudo-class ``:hover``
```CSS
.cards > div:hover {
    transform: scale(1.04, 1.04);
    box-shadow: 3px 2px 5px rgb(85, 111, 134);
}

```
To apply the margin-top property from the second card onwards, on the mobile layout, I used the  pseudo-class ``:nth-of-type(n)`` associated with the general sibling selector ``~``
```CSS
.top-destinations div:nth-of-type(1)~div, .best-deals div:nth-of-type(1)~div {
    margin-top: .75em;
}
```
In addition to those I mentioned, there were other examples of using the pseudo-classes and advanced selectors, like the adjacent sibling selector ``+``, the pseudo-class ``:first-of-type``, ``last-of-type``, ``:nth-child(n)``.

### 🛠️ Continued development
- Developing other pages to the website, like the Login page.
- Coding refactoring
- Develop the inputs validation

---
### Useful resources
- [CSS-Tricks Guides](https://css-tricks.com/guides/) - Useful guides to learn and consult about CSS custom properties.

