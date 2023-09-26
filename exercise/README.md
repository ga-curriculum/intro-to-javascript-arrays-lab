# Intro to Javascript Arrays Lab - Lab Exercise

![Hero image](./assets/hero.png)

<img src="https://i.imgur.com/sA6iEbw.jpg">

# JavaScript Arrays Lab

## Introduction

This lab provides an opportunity to practice defining, accessing and manipulating arrays.


### A Quick Note Before You Dive into JavaScript Arrays

Working with arrays is a fundamental skill in JavaScript, and this lab is designed to help you master it. As you navigate through the exercises, remember that the lesson materials on arrays are your first resource. They contain valuable examples and explanations that can clarify any uncertainties you might have.

Collaboration is key in coding—don't hesitate to discuss these exercises with your peers. Sharing your approaches to array manipulation can lead to deeper understanding and new learning opportunities.

Lastly, the internet is filled with extensive resources specific to JavaScript arrays. Websites like [Google](https://www.google.com/), [MDN Web Docs on Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array), and [Stack Overflow](https://stackoverflow.com/questions/tagged/javascript+arrays) are just a few clicks away. Don't shy away from using them to enrich your learning. Happy coding!



## Exercise

The following content should be copy and pasted into your Javascript file. Check your work by opening in the browser or using node in your terminal. 


```js
/*
Exercise 1: Define an Empty Array

1) Here, we want to create an array without any items initially.
*/

const foods = [];  // Exercise 1 has been completed for you...

console.log('Exercise 1 Result:\\n', foods);

/*
Exercise 2: Add Strings to the Array

1) Add 'pizza' and 'cheeseburger' to the `foods` array in that order.
*/

// Complete Exercise 2 below...



console.log('Exercise 2 Result:\n',  foods);

/*
Exercise 3: Insert at the Beginning

1) Insert the string 'taco' at the beginning of the `foods` array.
*/

// Complete Exercise 3 below...



console.log('Exercise 3 Result:\n', foods);

/*
Exercise 4: Access an Array Element

1) Retrieve the 'pizza' string from the array based on its position and assign it to a variable called "favFood".
*/

// Complete Exercise 4 below...



console.log('Exercise 4 Result:\n', favFood);

/*
Exercise 5: Insert an Element in Between

1) Insert the string 'tofu' between 'pizza' and 'cheeseburger' in the array.
*/

// Complete Exercise 5 below...



console.log('Exercise 5 Result:\n', foods);

/*
Exercise 6: Replace Elements

1) Replace 'pizza' in the `foods` array with 'sushi' and 'cupcake'.
*/

// Complete Exercise 6 below...



console.log('Exercise 6 Result:\n', foods);

/*
Exercise 7: Using `slice` Method

1) Use the `slice` method to create a new array that contains 'sushi' and 'cupcake' and assign it to a variable named "yummy".
*/

// Complete Exercise 7 below...



console.log('Exercise 7 Result:\n', yummy);

/*
Exercise 8: Finding an Index

1) Using the indexOf method, find the index of the string 'tofu' in the `foods` array. Assign it to a variable names "soyIdx".
*/

// Complete Exercise 8 below...



console.log('Exercise 8 Result:\n', soyIdx);

/*
Exercise 9: Joining Elements

1) Use the `join` method to concatenate all strings in the array, separated by ' -> '. Assign to a variable called "allFoods". 

2) The final result should log as:
'taco -> sushi -> cupcake -> tofu -> cheeseburger'
*/

// Complete Exercise 9 below...



console.log('Exercise 9 Result:\n', allFoods);

/*
Exercise 10: Check for Element

1) Using the .includes() method, check if the array contains the string 'soup'. Assign the boolean result to a variable called "hasSoup".
*/

// Complete Exercise 10 below...



console.log('Exercise 10 Result:\n', hasSoup);

/*
Exercise 11: Odd Numbers from Array
  
1) Chose a method iterate through the "nums" array and push each odd number to a new array named odds.

Hint: Initialize the odds variable to an empty array before the iteration.
*/

const nums = [100, 5, 23, 15, 21, 72, 9, 45, 66, 7, 81, 90];

// Complete Exercise 11 below...



console.log('Exercise 11 Result:\n', odds);

/*
Exercise 12: FizzBuzz with Arrays

1) Choose a method to iterate through the "nums" array. As you loop, you will be sorting numbers into new arrays based on the following criteria:

- Push to an array called fizzbuzz: any number that is evenly divisible by 3 & 5.
- Push to an array called fizz: any number that is evenly divisible by 3.
- Push to an array called buzz: any number that is evenly divisible by 5.
*/

// Complete Exercise 12 below...



console.log('Exercise 12 Results:');
console.log('  fizz:', fizz);
console.log('  buzz:', buzz);
console.log('  fizzbuzz:', fizzbuzz);

/*
Exercise 13: Retrieve the Last Array

1) Given a two-dimensional array (array of arrays) called numArrays, assign the last nested array to a variable named "numList".

2) Assume you don't know how many nested arrays numArrays contains.
*/

const numArrays = [
	[100, 5, 23],
	[15, 21, 72, 9],
	[45, 66],
	[7, 81, 90]
];

// Complete Exercise 13 below...



console.log('Exercise 13 Result:\n', numList);

/*
Exercise 14: Accessing within Nested Arrays

1) Retrieve the number 66 from the `numArrays` array and assign it to a variable called "num".
*/

// Complete Exercise 14 below...



console.log('Exercise 14 Result:\n', num);

/*
Exercise 15: Nested Array Sum

1) Use nested loops or `forEach` methods to sum up all numbers within the nested arrays and assign the sum to a variable called "total".

Hint: Be sure to declare and initialize the total variable before the iterations.
*/

// Complete Exercise 15 below...



console.log('Exercise 15 Result:\n', total);
```

**You did it!**
