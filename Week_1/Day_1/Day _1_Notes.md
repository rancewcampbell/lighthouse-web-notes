# Day 1 Notes

## Command Line Arugments

```
[runtime] [script_name] [argument-1 argument-2 ...]
```

* Runtime is anything that executes a program i.e. node. Arguments usually separated by a space.

* Command line arguments are passed as strings into program.

## process.argv

* Simplest way of retrieving arguments in Node.js

* First element is file system path pointing to node executable

* Second element is the name of the JS file being executed.

* Third element is actual first argument.

## minimist.js

* Allows access to the `process.argv` array in an easier manner by allowing access to the elements using index names as well as index numbers.

* To assign CLA a name use a flag followed by the value: `$ node minimist.js -i rance -j 25`

## yargs

* yargs acts more like an object. You can access arguments using `.` notation and set the values like so:
`$ node yargs.js --name=rance --age=25`

* The `.command()` option helps create and call Node functions from command line.

## Assertions

* `console.assert()` is a way to test code for bugs. Not common but one method.