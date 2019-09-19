# Day 2 (8 hours)

## BJSP: Data structures (2 hours)
#### Course Path
- [JS Info: Array Methods](https://javascript.info/array-methods)
- [Medium: Data structures in JS](https://medium.com/siliconwat/data-structures-in-javascript-1b9aed0ea17c)
- [Medium: Data structures in JS Part 1](https://blog.bitsrc.io/data-structures-in-javascript-part-1-8231c9a4bc8b)
- [Medium: Data structures in JS Part 2](https://blog.bitsrc.io/data-structures-in-javascript-part-2-d0d09b761df0)

## BJSP: Basics of DOM and DOM Manipulation (3 hour)
#### Course Path
- [JavaScript DOM Crash Course - Part 1](https://www.youtube.com/watch?v=0ik6X4DJKCc)
- [JavaScript DOM Crash Course - Part 2](https://www.youtube.com/watch?v=mPd2aJXCZ2g)
- [JavaScript DOM Crash Course - Part 3](https://www.youtube.com/watch?v=wK2cBMcDTss)
- [JavaScript DOM Crash Course - Part 4](https://www.youtube.com/watch?v=i37KVt_IcXw)

#### Additional References
- [MDN: Document Object Model](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- [DOM Manipulation Methods](https://www.hongkiat.com/blog/dom-manipulation-javascript-methods/)
- [Freecodecamp: DOM manipulation in Vanilla JS](https://www.freecodecamp.org/news/dom-manipulation-in-vanilla-js-2036a568dcd9/)
- [MDN: Manipulating documents](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents)


## BJSP: Debugging (30 min)
#### Course Path
- [Debugging techniques with Javascript](https://www.youtube.com/watch?v=3EXNtmgf87s)

#### Additional References
- [Debugging techniques with Javascript](https://www.youtube.com/watch?v=3EXNtmgf87s)
- [Googler Devs: Chrome devtools](https://developers.google.com/web/tools/chrome-devtools/javascript/)
- [JS debugging tips](https://raygun.com/javascript-debugging-tips)
- [JS Info: Debugging Chrome](https://javascript.info/debugging-chrome)


## BJSP Assignment: Remove Duplicate (2 hours 30 min)
#### Problem Statement
Given an array of numbers with duplicate values, write a function to return an array of approximately equally divided sorted array of unique numbers. For example, if the user provides an array of numbers say
> [1, 10, 20, 2, 5, 2, 2, 2, 5, 3, 4, 8]

Here, numbers = 1.....20 and array of numbers = [1, 10, 20, 2, 5, 2, 2, 2, 5, 3, 4, 8]

Your function should return an array of **equally** divided array of **sorted** numbers in **ascending** order after **removing the duplicates**. So, the result for the above would look like:
> [[1,  2, 3, 4], [5, 8, 10, 20]]

Now, if the total count of numbers is uneven and the array cannot be divided into exactly 2 arrays of same length, then add the remaining number in the first array. So say, we have an array:
> [1, 3, 2, 2]

Then, the final result would be:
> [[1, 2], [3]]

#### Input
[1, 9, 2, 3, 3, 3, 3, 3, 4, 4, 5, 6, 7, 8, 5, 6, 6, 9, 10, 10]

#### Output
[[1, 2, 3, 4, 5], [6, 7, 8, 9, 10]]

#### Constraints
- 1 < number < 10^3
- 2 < Array of numbers < 10^3
