# Day 4 Notes:

## JSON

* Serialization is the process of translating data structures or objects state into a format that can be stored (in a file or buffer etc.) or transmitted and reconstructed later. The opposite is called deserialization.

* JavaScript uses the JSON object for serializing and deserializing.

* `JSON.parse()` -> Parse a string as JSON, optionally transfor the produced value and its properties, and return the value.

*`JSON.stringify()` -> Return a JSON string corresponding to the specified value, optionally including only certain properties or replacing property values in a user-definded manner. 

* a 'media type' is a two-part identifier for file formats and format contents transmitted on the Internet.
  * JSON data Media Type is application/json and is set via the Content-Type http response header.

## APIs (Application Programming Interface)

* APIs are sets of requirements that govern how one application can talk to another.

* REST API stands for Representaional State Transfer API


## Lecure

* To fix 'callback hell' use promises.

* A promise has three values : resolved, pending, rejected.

* Start with something that starts the promise then use .then to continue ladder.


## Readings 

* Promises wrap callbacks. The use of promises doesn't mean callback are not necessary.

