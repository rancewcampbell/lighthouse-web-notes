# Day 4

## Front-end

### Positioning

* `position: static` will set elements as intended. They will not accept any specific box offset properties

* `position: relative` is similar to `position: static` except it accepts a property of top, right, bottom, and left and offsets accordingly

* `position: absolute` is removed from the normal flow of the document and still accept box offset properties.

* `position: fixed` works like absolute, but the element will not scroll with the page.

* To apply a z-index the position must be relative, fixed, or absolute

## Lecture notes

* Two types of html tags: content & divider

* Use kebob case when naming things i.e. kebob-case-class-name

* !important will override all specificity.

* structure css file based on HTML pattern eg top to bottom sections.

* only adjust the width of an image or adjust width and set height to 100%

* start w/ padding then try margin

* change one thing at a time

* turn `flex` on on the parent element, not child.

## Specificity 

* Put styles in LVHA order (link, visited, hover, active).

* Use least number of selectors on element possible.