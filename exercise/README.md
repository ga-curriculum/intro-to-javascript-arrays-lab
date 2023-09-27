# Intro to Javascript Arrays Lab - Lab Exercise

![Hero image](./assets/hero.png)

<img src="https://i.imgur.com/sA6iEbw.jpg">

# JavaScript Arrays Lab

## Introduction

This lab provides an opportunity to practice defining, accessing and manipulating arrays.

### A quick note before you dive in

If you find yourself stuck during the lab, we encourage you to first revisit the lesson materials. They're designed to provide you with the information and examples that will help you complete the exercises. 

If you've revisited the materials and are still facing challenges, don't hesitate to collaborate with your classmates.

Lastly, the internet is filled with resources specific to JavaScript arrays. Websites like [Google](https://www.google.com/), [MDN Web Docs on Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array), and [Stack Overflow](https://stackoverflow.com/questions/tagged/javascript+arrays) are just a few clicks away. Use these as a last resort, before reaching out for help.

Happy coding!


## Lab Exercises

Copy and paste each of the following exercises into your JavaScript file. To check your work, open the file in a web browser and inspect the console output, or run the file in your terminal using `node script.js`. 



### Exercise 1: Define an Empty Array

```js
/*
Exercise 1: Define an Empty Array

1) Create and empty array and assign it to a variable called "foods".

Exercise 1 has been completed for you:
*/

const foods = [];  



console.log('Exercise 1 Result:', foods);
```


### Exercise 2: Add Strings to the Array
```js
/*
Exercise 2: Add Strings to the Array

1) Add 'pizza' and 'cheeseburger' to the `foods` array in that order.

Complete Exercise 2 in the space below:
*/



console.log('Exercise 2 Result:',  foods);
```

### Adding to the front of an Array

**We know that `push()` and `pop()` are helpful methods for adding and removing items at the end of an array, but have you heard of  `shift()` and `unshift()`?**

The `shift` and `unshift` methods provide an easy way to manipulate elements at the beginning of an array. 
The unshift method *adds* one or more elements to the start of the array and returns the new length, while the shift method *removes* the first element from an array and returns that element. 

These methods are handy for scenarios where you need to quickly adjust the contents of an array without affecting elements at other positions.

shift: [*read the docs*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift)
<br>
unshift: [*read the docs*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift)


### Exercise 3: Insert at the Beginning
```js
/*
Exercise 3: Insert at the Beginning

1) Insert the string 'taco' at the beginning of the `foods` array.

Complete Exercise 3 in the space below:
*/



console.log('Exercise 3 Result:', foods);
```

### Exercise 4: Access an Array Element
```js
/*
Exercise 4: Access an Array Element

1) Retrieve the 'pizza' string from the array based on its position (index) in the array.  

2) Assign it to a variable called "favFood".

Complete Exercise 4 in the space below:
*/



console.log('Exercise 4 Result:', favFood);
```

### Adding and removing elements anywhere in an array

The `splice()` method is capable of **adding or removing** any number of elements inside an array. You can even take both actions simultaneously with a single line of code!

If we [*read the docs*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice), we'll find the syntax to be:

splice(start)<br>
splice(start, deleteCount)<br>
splice(start, deleteCount, item0)<br>
splice(start, deleteCount, item0, item1)<br>
splice(start, deleteCount, item0, item1, /* …, */ itemN)<br>

This syntax may seem overwhelming at first glance, but it means that all but the first parameter is optional - so when we call splice(), its behavior will change depending on how many arguments we pass to it. Give it a try!


### Exercise 5: Insert an Element in Between
```js
/*
Exercise 5: Insert an Element in Between

1) Insert the string 'tofu' between 'pizza' and 'cheeseburger' in the array.

Complete Exercise 5 in the space below:
*/



console.log('Exercise 5 Result:', foods);
```


### Exercise 6: Replace Elements
```js
/*
Exercise 6: Replace Elements

1) Replace 'pizza' in the `foods` array with 'sushi' and 'cupcake'.

Complete Exercise 6 in the space below:
*/



console.log('Exercise 6 Result:', foods);
```

### Copying parts of an array

The `slice()` method is used to extract a portion of an array and create a new array without modifying the original.

[*read the docs*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)

### Exercise 7: Using `slice` Method
```js
/*
Exercise 7: Using `slice` Method

1) Use the `slice` method to create a new array that contains 'sushi' and 'cupcake'.

2) Assign it to a variable named "yummy".

Complete Exercise 7 in the space below:
*/



console.log('Exercise 7 Result:', yummy);
```

### Searching for items within an array

The `indexOf()` method searches for a specified element within an array and returns the index of the first occurrence. If the element is not found, it returns -1.

[*read the docs*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf)

### Exercise 8: Finding an Index
```js
/*
Exercise 8: Finding an Index

1) Using the indexOf method, find the index of the string 'tofu' in the `foods` array. 

2) Assign it to a variable named "soyIdx".

Complete Exercise 8 in the space below:
*/



console.log('Exercise 8 Result:', soyIdx);
```

### Turning an entire array into a string

The `join()` method combines all the elements of an array into a single string, separated by a specified delimiter. 

[*read the docs*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/join)

### Exercise 9: Joining Elements
```js
/*
Exercise 9: Joining Elements

1) Use the `join` method to concatenate all strings in the array, separated by ' -> '. 

2) Assign to a variable called "allFoods". 

3) The final result should log as:
'taco -> sushi -> cupcake -> tofu -> cheeseburger'

Complete Exercise 9 in the space below:
*/



console.log('Exercise 9 Result:', allFoods);
```

## Checking for specific elements in an array

The `includes()` method checks if an array contains a specific element, returning a boolean value (true or false). 

[*read the docs*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)


### Exercise 10: Check for Element
```js
/*
Exercise 10: Check for Element

1) Using the .includes() method, check if the array contains the string 'soup'. 

2) Assign the boolean result to a variable called "hasSoup".

Complete Exercise 10 in the space below:
*/



console.log('Exercise 10 Result:', hasSoup);
```

## Let's take it up a notch

### Looping and Manipulating

Several methods exist for iterating through arrays in JavaScript. 

**For Loop**
The traditional for loop can be used to iterate through an array by index.

```js
for (let i = 0; i < arr.length; i++) {
  console.log(arr[i]);
}
```

**For...of Loop**
The for...of loop allows you to loop through the values of an array directly, without using an index.

```js
for (const element of arr) {
  console.log(element);
}
```

**forEach Method**
The forEach method performs a given function on each element of an array.

```js
arr.forEach(element => {
  console.log(element);
});
```

Choose one to practice with for these next few exercises! 


### Exercise 11: Odd Numbers from Array
```js
/*
Exercise 11: Odd Numbers from Array
  
1) Chose a method iterate through the "nums" array and push each odd number to a new array named "odds".

Hint: Initialize the odds variable to an empty array before the iteration.

Complete Exercise 11 in the space below:
*/

const nums = [100, 5, 23, 15, 21, 72, 9, 45, 66, 7, 81, 90];



console.log('Exercise 11 Result:', odds);
```

### Exercise 12: FizzBuzz with Arrays
```js
/*
Exercise 12: FizzBuzz with Arrays

1) Choose a method to iterate through the "nums" array. As you loop, you will be sorting numbers into new arrays based on the following criteria:

- Push to an array called fizzbuzz: any number that is evenly divisible by 3 & 5.
- Push to an array called fizz: any number that is evenly divisible by 3.
- Push to an array called buzz: any number that is evenly divisible by 5.

Complete Exercise 12 in the space below:
*/



console.log('Exercise 12 Results:');
console.log('  fizz:', fizz);
console.log('  buzz:', buzz);
console.log('  fizzbuzz:', fizzbuzz);
```

### Working with two-dimensional arrays

A two-dimensional array is essentially an "array of arrays" in programming. Sometimes referred to as "nested" arrays. 

```js
const twoDArray = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]
];
```

 - In a one-dimensional array, you access elements using a **single index**. 
 - In a two-dimensional array, you use **two indices**: one for the "row" and another for the "column." 

This creates a structure similar to a grid or a table.


### Exercise 13: Retrieve the Last Array
```js
/*
Exercise 13: Retrieve the Last Array

1) Given a two-dimensional array (array of arrays) called numArrays, assign the last nested array to a variable named "numList".

2) Assume you don't know how many nested arrays numArrays contains.

Complete Exercise 13 in the space below:
*/

const numArrays = [
	[100, 5, 23],
	[15, 21, 72, 9],
	[45, 66],
	[7, 81, 90]
];



console.log('Exercise 13 Result:', numList);
```


### Exercise 14: Accessing within Nested Arrays
```js
/*
Exercise 14: Accessing within Nested Arrays

1) Retrieve the number 66 from the `numArrays` array and assign it to a variable called "num".

Complete Exercise 14 in the space below:
*/



console.log('Exercise 14 Result:', num);
```

### Looping though nested arrays

To loop through a two-dimensional array, you'll typically use nested loops: one loop for the **rows** and another for the **columns** within each row.


### Exercise 15: Nested Array Sum
```js
/*
Exercise 15: Nested Array Sum

1) Use nested loops or `forEach` methods to sum up all numbers within the nested arrays and assign the sum to a variable called "total".

Hint: Be sure to declare and initialize the total variable before the iterations.

Complete Exercise 15 in the space below:
*/



console.log('Exercise 15 Result:\n', total);
```

<br>

**🎉  The End. You did it!  🎉**
