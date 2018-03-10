## Javascript Snippets
This is a list of code snippets which I find useful. This list will be used as a reference and is regularly updated.

### Setting default value with ```||``` operator
```
function greet (name) {
  name = name || '<Your name here>';
  console.log('Hello ' + name);
}

greet('Angus'); // returns 'Hello Angus' or first 'true' value.
greet(); // returns 'Hello <Your name here>' or first 'true' value.
```
## Author

Angus Clark
