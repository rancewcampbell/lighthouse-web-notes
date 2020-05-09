# REACT!!!
------------

* React is declarative which makes the code easier to read.

* It is component based to allow an application to be split into smaller components.

* Good components are composable, encapsulated, reusable and testable. Ideally they have a single responsibility.

## Imperative vs. Declarative Programming
------------
* Imperative describes HOW something is to be done: 
```js
const add = (arr) => {
  let result = 0;
  for (let i = 0; i < arr.length; i++) {
    result += arr[i];
  }
  return result;
};
```

* Declarative describes WHAT is to be done: 
``` js
const add = (arr) => {
  return arr.reduce((a, b) => a + b, 0);
};
```

## State & Props
--------------

* In a React component, props are variables passed to it by its parent component. 

* State on the other hand is still variables, but directly initialized and managed by the component.

* The state can be initialized by props.