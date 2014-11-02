Save-JS-Console-Output
======================

Add "console.save" to your console object.  console.save(<object>) will create a json file of the object you save, and immediately download it.  I find this useful for a number of things.

Example:
```JavaScript
var data = { 
  hey: "ho",
  key: "value
}

console.save(data, 'whatever.json'); // this automatically downloads/formats the "data" object to "whatever.json"
```
