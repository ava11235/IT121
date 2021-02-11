## Document Object Model
## Reading

zyBooks Ch 6

DOM specifies how a browser creates a model of an HTML page and how JS can accesses or modify an HTML page. 

The DOM tree is a represenation of a web page.

To access and update the HTML on a web page you need to select the element(s) to work with. 

Some of the ways ways to select element nodes inlcude: 

```getElementById(‘one’);
getElementsByClassName(‘red’);
getElementsByTagName(‘p’);
querySelector(‘#one’);
querySelectorAll(‘ul.li’);
```

Some DOM queries return more than one element as a nodeList. The elements returned are indexed.
It is possible to move from one node to another if it is a relation of it.

Elements can contain:
Text nodes

Element content

Attributes

Properties for accessing the content include: 

```nodeValue 
textContent 
innerHTML
```


## Examples
https://codepen.io/mickeysthecat/pen/VwmKowd

## Reference
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model

## Practice
 
zyBooks Ch 6 (graded participation activity)

## Learning Outcomes
Upon successful completion of the work, students will be familiar with and able to apply the below concepts and techniques in their programs

* Work with JS in the browser
* Be able to represent the HTML document as a DOM tree of nodes.
* Use DOM object methods to search the DOM
* Use DOM methods to modify DOM attributes
* Use DOM methods to access nodes
* Use DOM methods to modify the DOM structure


