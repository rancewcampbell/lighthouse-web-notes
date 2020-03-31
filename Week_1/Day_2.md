# Day 2 Notes

## From Eloquent JS

* Keep function names explicit, but keep names as short as possible.

* From Ch 3: "A useful principle is to not add cleverness unless you are absolutely sure you’re going to need it. It can be tempting to write general “frameworks” for every bit of functionality you come across. Resist that urge. You won’t get any real work done—you’ll just be writing code that you never use."

* A 'pure' function has no side effects and does not rely on side effects from other code either.

* Some operations can be expressed more effieciently with side effects. Computing speed can be a reason to sacrifice

## Function Best Practices 

1. Give your functions precise verb/action based names

2. Use camelCaseNames

3. Properly indent

4. Functions should have one task: returning a value or causing a side effect.

5. "It is ideal if functions try to avoid reading outer scope variables. If a function needs some information / data, then that data should instead be passed in as a parameter, making it available within the function's inner scope."

## Error Messages

* Syntax Error -> something wrong with how the program is typed
  * Unexpected token -> Javascript expected something that wasn't there

* Reference Error -> occur when trying to use the value of an undefined variable.

* Type Errors -> occur when the type doesn't match what you're trying to do i.e. calling a function that isn't a function.

## Lecture Notes

* Before running `git init` run `git status` to avoid nested repos.

* No need to initialize a repo when cloning a repo.

* Cause errors first. It is better to control the errors instead of having the errors control you.

* To get it to stop asking for username and password use the SSH

* Use the more verbose command line arguments