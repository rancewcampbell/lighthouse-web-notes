# Day 3 Notes

## Objects

### Data Types:

* Six primitive data types:
  1. undefined
  2. null
  3. boolean
  4. string
  5. number
  6. symbol

* Anything that is not an Object is a primitive.

### Objects
Objects:
* Key-value pairs
* Key is always a string
* Key cannot appear twice in object
* Value can be of any type

Object Literals:
`const emptyObject = {};`
`const tinyObject = { size: 'Tiny' }`

* To inspect an object's keys use:
`Object.keys(...)`
which returns an array of keys.

* To loop over an object, use `for ... in`
  * use `object.hasOwnProperty(key)` to filter out unexpected results.

* primitive data types can be coerced to being an object which allows things like `string.length`


## Lecture Notes:

* Read code like Javscript would.

* When assigning an array to another location, the data doesn't copy over. It is simply a reference to the same array.

* With primitive data types, we copy the value

* With non-primitive we copy the reference

* When using `this` in a method, it always refers to the object.
