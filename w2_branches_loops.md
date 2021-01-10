## Reading

### Conditional Statements
A Conditional Statement is a group of commands that  are executed only if a condition is true. The conditional statement is built with an if statement and the optional else if
or else statements.

```
if (condition_1) {
  statement_1;
} else if (condition_2) {
  statement_2;
  ...
} else {
  statement_last;
}
```
Another structure for writing conditional statements is the switch statement.  The program looks for a matching label value. If this value is found, the corresponding code 
is executed. If no matching label is found, the default clause is executed. Note that the default is optional. If no default is found, the code after the switch statement
will be executed.

```
switch (label) {
  case label_1:
    statements_1
    [break;]
  case label_2:
    statements_2
    [break;]
    …
  default:
    statements_def
    [break;]
}
```

## Example
[Branches](https://codepen.io/mickeysthecat/pen/jOMpaJq)

## Loops
Loops, or iteration statements, are used to execute the same code repeatedly. There are several loops statements available in JavScript. 

for statement
```
for ([initialExpression]; [conditionExpression]; [incrementExpression]) {
  statement;
  statement ;
  }```

while statement

```while (condition) {
  statement;
  statement ;
 } ```

do whlie statement

```do {
    statement;
    statement;
   } while (condition);
``` 
The difference between the while and do...while loops is that with the do...while loop the statements are always executed once before the condition is checked.

## Example
[Loop](https://codepen.io/mickeysthecat/pen/KKgByLM)

## Reference
https://developer.mozilla.org/en-US/docs/Web/JavaScript
https://hackernoon.com/understanding-js-coercion-ff5684475bfc

https://developer.mozilla.org/en-US/docs/Glossary/Truthy

https://developer.mozilla.org/en-US/docs/Glossary/Falsy

Another cloud editor recommendation: https://codepen.io/

## Practice

zyBooks Ch 2 Practice (graded participation activity)

## Learning Outcomes
Upon successful completion of the work, students will be familiar with and able to apply the below concepts and techniques in their programs

* What are conditional statements and how to implement them in JS: if and switch
* What are comparison operators
* Nested if statements
* Logical operators: AND, OR, NOT
* Truthy and falsy values 
* Ternary operator
* What are loops and how to implement them in JS: for, while, do...while



