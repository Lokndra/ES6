# ES6

ES6 stands for ECMAScript 6 and is a significant update to JavaScript language. ES6 is the 6th version of ECMAScript, it had been published in 2015.

## BASIC DATA TYPES

Like other languages Variables in JavaScript aren't directly related to any particular value type, and any variable could be assigned and re-assigned values of all types:

` let a = 45; `

Here variable a is of integer type we can reassign it to any other data type like:

```javascript
a = "Hi";`
a = true;
```

There are five types of basic used data types are there in ES6:-

### NUMBER

The number is a data type used to store any numerical and decimal values We can declare and assign any numerical and decimal number by using integer data type like:

```javascript
let a = 43;
let b = 43.33;
```

### STRINGS

Strings are defined as a sequential collection of characters. The string must be surrounded by quotes. In JavaScript, there's no special character data type. There’s just one type: string. A string may contain zero characters (be empty), one character, or many of them.

```javascript
let a = "LOKENDRA";
let b ='H';
let c= "";
```

### BOOLEAN

The Boolean data type can only have two values true and false. Here true mean yes and false means no. We can also use boolean to check the results of comparisons like:

```javascript
let isgreater =4>1
console.log(isgreater)
```

In the above example, isgreater value will be printed true because here 4 is greater than one.

### NULL

This type has only one value that is null.

`let age = null`;

### UNDEFINED

If we declare a variable, but not assign it, then its value is undefined:

```javascript
let age;
console.log(age);
```

When we will run the above example it will show undefined. Technically, it's possible to assign undefined to a variable.

```javascript
let age = 100;
age = undefined;
console.log(age); 
```

When we will run the above code it will also show undefined because we have assigned age to undefined.

## BASIC DATA STRUCTURES

Any structure that holds the data and exhibits some Behaviors is a data structure. Basic used data structures are:

### ARRAY

The array is an indexed collection of data. It's a special variable that can store more than one value at a time. We can declare and assign arrays like:

```javascript
let marks =[33,44,55,66,77];
let oranges =["oranges","apple","grapes"];
let boolean =[true,false,true];
let result =[45.5,69.4,77.9,79.8];
```

We can also declare arrays with different values like:

`let mixed =[34,'hi',67.9,true]`

### QUEUE

The Queue is a data structure that can hold the data and exhibit orderly insertion and deletion of data. The Queue has first in first out orderly insertion and deletion. That is the element that is inserted first would be deleted first. After creating a queue, we can use the enqueue and dequeue functions to add items to the end of the queue and remove them from the front:

```javascript
let queue = new Queue();
queue.enqueue('item1');
var item1 = queue.dequeue();
```

### MAP

The map is a collection that store data in key-value pairs where keys can be of any type. A new Map can be created like:

```javascript
let map = new Map();
map.set('firstname', 'Lokendra');
map.set('middlename', 'singh');
map.set('lastname', 'Thakur');
```

### SET

A set is a unique collection of elements that can be of any type. It's an ordered collection so we can retrieve elements in the same order it's inserted. We can create and insert elements in a set like:

```javascript
let set = new Set();
set.add('tomato');
set.add('avocado');
set.add('carrot');
set.add('cucumber');
set.add('cucumber');
console.log(set);
```

In the above code, we have added cucumber 2 times in set, but it will show it only once in the output because we can only add unique values.

` Set(4) {"tomato", "avacado", "carrot", "cucumber"} `

### LINKEDLIST

The LinkedList is a linear data structure in which each element is connected with the next element. We can create LinkedList like:

```javascript
let list = new LinkedList();
list.add("Lokendra");
```

### STACK

The stack is a data structure that can hold the data and exhibit orderly insertion and deletion of data. The Queue has last in first out orderly insertion and deletion. That is the element that is inserted last would be deleted first. After creating a stack, we can use the push and pop functions to add and remove items.

```javascript
let stack =  new Stack();
stack.push(1);
let item  =  stack.pop();
```

## REFRENCES

1. <https://youtu.be/bpdvNwvEeSE.>
2. <https://youtu.be/Hrd3SfCCXZw>.
3. <https://www.educative.io/blog/javascript-data-structures>
