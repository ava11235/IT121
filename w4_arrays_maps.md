## Arrays and Objects
## Reading

## Arrays
Ch 4.2 Arrays 


 An array is a list of sequential items that can be accessed with an index.
 To create a literal array, use this syntax:
 
 ```
 let shoppingList = ['bread', 'rice', 'potatoes', 'beans', 'kale'];
 
 //print an the entire array content 
  console.log(shoppingList);
 
 //use the index to access individual elements of the array
 console.log(shoppingList[2]; //potatoes 
 
 ```
 
 
 The array object supports various methods for working with arrays. 
 
 Click on each link for interactive examples.
 
 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/length
 
 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
 
 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse

There are several methods available for iterating over an array's elements such as:

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of

or the standard ```for loop ``` using the length of the array
```
for (i = 0; i < shoppingList.length; i++) {
   console.log(i + 1 + " " + shoppingList[i]);
}
```

## Maps
## Ch 4.3 Maps

A map is a key-value pair ordered object, such as: state and its state bird.

The object map supports methods for getting the number of elements, removing elements, checking if a key is in the map, and setting a map's key and value.

``` let stateBirds = {
   WA: "American goldfinch",
   OR: "Western meadowlark",
   ID: "Mountain bluebird"
};

//single key
console.log("WA's state bird is " +  stateBirds["WA"]);

//iterate over entire map

for (let state in stateBirds) { 
   console.log(state + "\'s state bird is " + stateBirds[state]);
}

```

Click on each link for interactive examples. 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/get

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/delete

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/forEach




## Reference
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map


## Practice
 
zyBooks 4.2, 4.3 (graded participation activity)

## Learning Outcomes
Upon successful completion of the work, students will be familiar with and able to apply the below concepts and techniques in their programs

* Define what an array, element and index is and implement arrays in JS.

* Be familiar and work with array methods for adding and removing array elements.

* Iterate through arrays using for, for..of, and forEach() methods.

* Be familiar with and work with array methods for searching or sorting arrays.

*  Define what a map (or associative array) is and implement it in JS. 

* Work with the elements of maps, known as key/value pairs.

* Use the for...in loop to iterate over maps.

* Work with the Object.keys(), in, and delete methods.

* Work with methods of the Map object to set, get or remove keys or values.
