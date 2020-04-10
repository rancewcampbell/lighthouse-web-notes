# OOP In Javascript

## Classes

* A class is a blueprint for an object. 

* Declare a class by using the `class` keyword. Always capitalize class names: 
```js
class Pizza {

}
```
* to create a new object from a class use the `new` keyword:

```js
let pizza1 = new Pizza();
let pizza2 = new Pizza();
```

* an object is an instance of the class.

* To add a method to a class us this syntax:

```js
class SomeClass {
  methodName(parameters) {
    // this is a method
  }
}
```

* `constructor` is a special method that is executed whenever a new instance is created. Everything inside `constructor` will get run for the new instance. This creates default values for each instance.

* Classes can inherit from other parent classes using the `extends` keyword -> 
```js
class Animal {
  // properties here
}

class Dog extends Animal {
  // I inherit properties from Animal
}
```

* child classes can overwrite parent class methods. 

* use `super` to access code that is already present in parent class when overriding methods.

### Getters and Setters:

```js
class Pizza {
  set size(size) {
    this.size = size;
  }
  get price() {
    return this.price;
  }
}
```
* Two reasons to use getters and setters:
  1. Validation data before assigning it to a property.
  2. Computing a value on the fly instead of simply pulling it out of a property.

* Use setter method to validate the setting of a value before the value actually gets set.

* Use a get method to compute values easier.

### More class talk

* Dependency Injection -> passing an object the things it needs rather than having the object access them itself