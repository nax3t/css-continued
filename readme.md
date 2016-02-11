# Continuing CSS

Review/Cold calling:

- HTML5 elements (header, nav, section, article, aside, footer, etc.) and attributes (src, alt, width, id, class, etc.)

![HTML5 layout](http://www.w3schools.com/html/img_sem_elements.gif)

- Anatomy of a css rule

![css rule](http://www.w3schools.com/css/selector.gif)

- Specificity

<img src="https://3oil7x2swx3d30yjgq23wmyu-wpengine.netdna-ssl.com/wp-content/uploads/2015/05/specificity1.png" width="425px">

- Box model

![Box model](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcQX1kvmTsfO6QJuWZwpnXUjyhNCW1SJDXDsnjsw7cFMYRuJVwb1)

- Box-sizing: border-box

![Box-sizing](http://bcfedigitalmedia.com/wordpress/wp-content/uploads/2015/11/box-sizing-property.jpg)

- [Pseudo class](https://developer.mozilla.org/en-US/docs/Web/CSS/pseudo-classes) (:hover, :focus, :active, :first-child, :nth-child(), etc)
"...specifies a special state of the element to be selected"
- [Pseudo elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements) (::after, ::before, ::first-letter, ::first-line, etc)
"...allow you to style certain parts of a document"
- [Floats and clear](https://css-tricks.com/all-about-floats/), are they [good to use for layouts](http://stackoverflow.com/questions/9776840/are-floats-bad-what-should-be-used-in-its-place)?
- Other ways to position? Run through the [ten steps of absolute and relative positioning](http://www.barelyfitz.com/screencast/html-training/css/positioning/)
- [Visibility:hidden vs display:none](http://stackoverflow.com/questions/133051/what-is-the-difference-between-visibilityhidden-and-displaynone) and an [example](http://codepen.io/nax3t/pen/bEOOPK)
- [Flex box playground](http://demo.agektmr.com/flexbox/)

## Normalize vs Reset
Discuss [normalize vs reset](http://stackoverflow.com/questions/6887336/what-is-the-difference-between-normalize-css-and-reset-css) and an [example](http://codepen.io/zachwolf/details/bdZMZj)

## Media queries
Discuss what they are, some of the common ones, how to use, etc.
Example:
```
@media (max-width: 600px) {
  .facet_sidebar {
    display: none;
  }
}
 ```
 
- [Mdn docs](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)
- [Stack overflow](http://stackoverflow.com/questions/16647380/max-width-vs-min-width)
- [CSS-Tricks](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)

## Positioning
- [Barelyfitz](http://www.barelyfitz.com/screencast/html-training/css/positioning/)
- [Quirksmode](http://quirksmode.org/css/css2/position.html)

## Flexbox
- [Playground](http://demo.agektmr.com/flexbox/)
- [MDN docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)
- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Scotch.io](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)
- [Collection of cool flexbox layouts](http://codepen.io/collection/KegmA/)
- [YouTube Tutorial](https://www.youtube.com/watch?v=G7EIAgfkhmg)

# 11am - 12:30pm Exercise: [Medium clone](https://medium.com/react-tutorials/react-components-828c397e3dc8#.hfq63kllb)
####You need to create a layout for a blog site that your company uses. There are essentially three content areas: the header (with logo), the post content (left column), the “Also read” posts (right column), and the footer.
###Expected Outcomes
- A github repo for each student called medium
- An external CSS page (no inline styles!)
- Use assets/content from the page (if you copy code, you aren’t learning)
- Page should look almost exactly like current medium page (https://medium.com/react-tutorials/react-components-828c397e3dc8)
- A basic media query should be used to make the columns collapse when the viewport width is less than 600px


