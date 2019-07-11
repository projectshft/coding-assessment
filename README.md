# Sample Challenges
These sample problems were created to help you gauge your current coding abilities. The prompts here are written in JavaScript, but feel free to use any language you're comfortable in. Get as far as you can - don't fret if you cannot finish all of the problems. 

## Problem One
Write a function that when invoked will log `'Star Wars is the best!'`

## Problem Two
Create a varible named after you and assign it to an object with the keys: age, height, hairColor, and an array called favoriteHobbies. You determine the values of these keys.

For example: I would name my variable `Aaron` and it would describe things about me when I reference it.

## Problem Three
Add a new property called **wave** to the object you created above. Give **wave** the value of a function that will return the string `'Hey everyone!'`.

## Problem Four
Using the same object, write some javascript that will give us the following output:
```JavaScript
'Hey everyone! My favorite hobbies are <hobbie1, hobbie2, hobbie3, etc.>'
// You will obviously list the hobbies you created in the array earlier.
```

## Problem Five
Write a function called `WorthTheWait` that takes in minutes as an argument (a number) and logs the string `'The line is too long!'` if the wait for the number passed in is over 60, or returns the string `'Let's do this!` if the number passed in is less than 60.

## Problem Six
Write a function that adds an array of numbers together. For example, a function invoked with this array, `[2, 3, 3, 4]` would return `12`. 

## Problem Seven
Write a function that counts the number of vowels in an array, given that the arrays if full of only letters. For example, a function invoked with `[i, a, e, t, i, i, a]` would return `6`.


## Problem Eight
Write a function that reverses a string. For example, if you invoked the function with the string `"Hello World and Coders"`, it would return `sredoC dna dlroW olleH`.

## Problem Nine
Write a function that takes an array of integers, and finds the pair of adjacent elements that has the largest product and return that product.

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
