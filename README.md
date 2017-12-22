# Sample Challenges
These smaple problems were created to help you gauge your abilities in javascript to see if you might be ready for the actual coding challenge. Feel free to practice these and other problems you find across the interwebs!

## Problem One
Write a function that when invoked will log `'Star Wars is the best!'`

## Problem Two
Create a varible named after you and assign it to an object with the keys: age, height, hairColor, and an array called favoriteHobbies. You determine the values of these keys.

For example: I would name my varible `Brett` and it would describe things about me when I reference it.

## Problem Three
Add a new property called **wave** to the object you created above. Give **wave** the value of a function that will return the string `'Hey everyone!'`.

## Problem Four
Using the same object, write some javascript that will give us the following output:
```JavaScript
'Hey everyone! My favorite hobbies are <hobbie1, hobbie2, hobbie3, etc.>'
// You will obviously list the hobbies you created in the array earlier.
```

## Problem Five
Write a function called `WorthTheWait` that takes the minutes parameter (passed as a number) and logs the string `'The line is too long!'` if the wait for the Roller Coaster is over 60 minutes, or returns the string `'Let's do this!` if the wait is below 60 minutes.

## Problem Six
Using some JavaScript, have the `function addAllItems(array)` take the array argument being passed and return the sum of all the items in the array. 

For example: if the input string is `[2, 3, 3]` then your program should return `8`. 

#### Sample Test Cases

```
Input: [3, 4, 2, 1]
Output: 10
```

```
Input: [3, 2, 10, 2]
Output: 17
```

```JavaScript
function addAllItems(array) { 

  // code goes here  
  return number; 
}
```
---

## Problem Seven
Using some JavaScript, have the `function numberOfVowels(str)` loop through the array being passed and return the total number of vowel letters that appear in the array. 

For example: if the input array is `[i, y, a, e, t]` then your program should return the number `3`. 

#### Sample Test Cases

```
Input: [i, q, j, a, k, c, e, e]
Output: 4
```

```
Input: [o, t, u, i, a, e, a, z]
Output: 6
```

```JavaScript
function numberOfVowels(array) { 

  // code goes here  
  return number;      
}
```
---


## Problem Eight
Using some JavaScript, have the `function firstReverse(str)` take the str argument being passed and return the string in reversed order. 

For example: if the input string is `"Hello World and Coders"` then your program should return the string `sredoC dna dlroW olleH`. 

#### Sample Test Cases

```
Input: "coderbyte"
Output: "etybredoc"
```

```
Input: "I Love Code"
Output: "edoC evoL I"
```

```JavaScript
function firstReverse(str) { 

  // code goes here  
  return str;        
}
```
---

## Problem Nine
Using some JavaScript, have the `function adjacentElementsProduct(array)` take an array of integers as the argument being passed, and find the pair of adjacent elements that has the largest product and return that product.

For example: if the input array is `[1, 3, 5, 8]` then the function should return `40`; because 5 * 8 = 40.

#### Sample Test Cases

```
Input: [5, 1, 2, 3, 1, 4]
Output: 6
```

```
Input: [9, 5, 10, 2, 24, -1, -48]
Output: 50
```

```JavaScript
function adjacentElementsProduct(array) { 

  // code goes here  
  return product;        
}
```
---

## Problem Ten
Imagine that you have been assigned to write a program for a school that needs to determine which test was the hardest for the students. Your program should be able to take an object as an argument that has a list of students with their respective list of grades. The output of the program should be able to clearly tell the user which test was the hardest (lowest class average).

#### Sample Test Cases

```javascript
Input: {
          Ron: [90, 89, 99, 87, 100, 74],
          Leslie: [78, 74, 92, 87, 77, 81],
          Tom: [77, 61, 89, 47, 57, 83],
          Andy: [35, 54, 44, 58, 39, 41]
        }
// The grades are in order by test number. The first index is test one, the second index is test 2, etc.

Output: 'The hardest test was test number 5'
```

```javascript
Input: {
          April: [88, 56, 55, 97, 100, 88, 100, 98],
          Tammy1: [78, 46, 92, 84, 55, 74, 89, 80],
          Ben: [77, 59, 89, 47, 57, 83, 90, 89],
          Garry: [54, 90, 84, 88, 39, 73, 67, 79],
          Tammy2: [86, 49, 90, 77, 89, 92, 88, 75]
        }
// The grades are in order by test number. The first index is test one, the second index is test 2, etc.

Output: 'The hardest test was test number 2'
```

---