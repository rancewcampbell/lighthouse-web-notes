# Day 2

## Dom events:

* when using callbacks in event handlers there are a few things to be aware of:

  1. when removing an event listener, I must have a reference to the original callback I am trying to remove.

  2. `bind` functions to keep function context when using a method etc.

* 'Bubbling' is the effect of a triggered event to move up through the DOM tree to the root. To stop bubbling, use `stopPropagation`.

* To stop all event listeners from being called on a particular node, use `stopImmediatePropagation`.

*  `preventDefault` prevents the browsers default response and allows custom response to happen.

* It is useful to delegate listeners to multiple elements instead of creating a separate listener for each element.

### Useful Events:

* `load` event will not fire until page has finished loading.

* `window.onbeforeunload` makes user confirm they want to leave page.

* `error` fires when an error occurs

## Lecture Notes:

* checkout window object for full functionality of browser.

* what creates the DOM?

* to show a jQuery object use a `$` at the beginning -> $obj

* to create an element in jQuery use `<>` i.e. `$('<li>')`