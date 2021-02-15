## Event Driven Programming and Modifying CSS with JS
## Reading

zyBooks Ch 7

## Events

Events are the browser’s way to notify  that something has occurred. 

When an event fires, your script can handle the event by running code such as a function.

When your code responds to the event and the user actions, the website becomes interactive.

There are different types of events such as UI events (e.g.load, resize), keyboard events (e.g keypress), mouse events (e.g. click), and form events (e.g. submit).

Events trigger JS code to run by: 

1.  Selecting the node the script will respond to.

2. Stating the event hat will trigger the response code on the selected node

3. Stating the code to run when the event occurs

There are three ways to bind an event to an element:

* HTML event handler attributes 
* Traditional DOM event handlers
* DOM Level 2 event listeners

HTML elements are nested inside other elements. For example, when clicking on a link, you are also clicking on the link's parent elements.

## Modifying CSS with JS

In addition to HTML elements, text and attributes, JS can manipulate the CSS on a page with the use of the CSS Object Model and the JS functions it provides.

CSS properties can be accessed, modified and deleted  with methods such as getPropertyValue(), setProperty(), and removeProperty().

CSS stylesheets can also be modified with methods such as insertRule() aned deleteRule().

CSS classes can be added or removed with the use of the classList property and methods such as add(), remove() and toggle(), and the className property.

## Examples


## Reference

https://developer.mozilla.org/en-US/docs/Web/Events

https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener

https://developer.mozilla.org/en-US/docs/Web/API/CSS_Object_Model/Using_dynamic_styling_information


## Practice
 
zyBooks Ch 7 (graded participation activity)

## Learning Outcomes
Upon successful completion of the work, students will be able to: 

* Define and work with event driven programming, event handlers and event listeners.
* Be familiar and work with common events such as click and mouseover.
* Be able to write event handlers for commonly used events in web development such as DOMContentLoaded, focus, blur, and submit.
* Write event handlers using different approaches such as embedding event handlers, setting event handler properties and using addEventListener().
* Be familiar with the event capturing, target and bubbling phases of an event.
* Prevent the default behavior of an event, such as opening a form when the user clicks on an element.
* Work with events related to timers and intervals rather than user actions.
* Modify CSS properties with JS
* Add and remove CSS classes with JS

