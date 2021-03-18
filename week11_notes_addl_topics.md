## Regular Expressions, Classes
## Reading

zyBooks 10.1 - 10.3
Optional, the rest of the Ch 10 topics.

### Regular Expressions
Regular expressions are used to match user input or other data, such as a user credit card number format or search and replace operations in large data sets.
A regular expression, aka regex, is a string pattern that is matched against a string. 
JS provides a RegExp object which can be used to define regular expressions. An alternative is adding the expression between forward slashes. e.g. /expression/

Regular expressions use special characters and metacharacters, to create more complex patterns. See the below regex reference for a comprehensive list.

The RegEx exec(str) method is used to determine a string match to a regex.

### Classes (ES 6)

What is ES*?

ECMAScript (/i.si.ɛmˈeɪskrɪpt/) (or ES)[1] is a general-purpose programming language, standardised by Ecma International according to the document ECMA-262.
It is a JavaScript standard meant to ensure the interoperability of Web pages across different Web browsers.[2] 
ECMAScript is commonly used for client-side scripting on the World Wide Web, and it is increasingly being used 
for writing server applications and services using Node.js.
https://en.wikipedia.org/wiki/ECMAScript

ES6 classes

A JavaScript class is a constructor function, which defines the properties and methods of an object.

Every JS object is associated with a prototype object.

In JavaScript you can create private properties by adding them to the constructor function and making them accessible with get and set properties.

JavaScript supports inheritance, however the implementation is more complicated than in other languages.
JavaScript does not support multiple inheritance.


### Examples

``` let reg1 = new RegExp("cat");
let reg2 = /cat/; 

console.log(/cat/.test("cat"));
// → true
console.log(/cat/.test("cats"));
// → false 
```


``` 
class Person {
   constructor(name, age) {
      this.name = name;
      this.age = age;
   }
    
   intro() {
      console.log("Hello.  My name is " + this.name + ". I am " + this.age + " years old.");
   }
}

let p1 =new Person("Amir", 29);
p1.intro();  

```

## Reference
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp

https://www.w3schools.com/jsref/jsref_obj_regexp.asp

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec

https://www.w3schools.com/js/js_object_constructors.asp

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures


## Practice
 
zyBooks 10.1, 10.2. 10.3 (graded participation activity)

## Learning Outcomes
Upon successful completion of the work, students will be able to: 

* Define what is a regular expression and use regular expressions to match string patterns.
* Create and use classes in JavaScript
