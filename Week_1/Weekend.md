# Weekend Notes:

## Exporting/Importing

* Every file in Node is a module

* In order to import code from one file to the other, use `require` and `module.exports`

* In the file that is exporting code write `module.exports =` whatever is being exported.

* To import that code into a file save it as a variable like this: `const somethingToImport = require('./path/to/module'):`

## Packages 

* To install packages into the current directory/project use `npm install [package]`

### Package.json

* the `scripts` portion of package.json makes it possible to run command using an alias:
  ```js
  "scripts": {
    "myscript": "ENV=develpment node index.js"
  }
  ```
  allows me to use this command:

  `npm run myscript`

  * The `dependencies` section of package.json is a list of packages that need to be installed for the project to run properly

  ## Testing

  * Start with a `describe` block

  * Inside the `describe` block there are `it` blocks

  * The first parameter to `it` should provide a human-readable descriptionof hte test. 

  * The code to implemetn the test is written in the callback function.

  * SUT or System Under Test is whatever I'm testing.

  * Last thing is to validate the test using an assertion function. These functions usually take the 'actual' value as the first argument and the 'expected' as the second.

  # Research Asynchronous Programming.