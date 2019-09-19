# Day 6

## AJC: 'this' keyword (1 hour)
#### Course Path
- [JS Info: Object Methods](https://javascript.info/object-methods)
- [Understanding the 'this' keyword in JS](https://medium.com/quick-code/understanding-the-this-keyword-in-javascript-cb76d4c7c5e8)


## AJC: Storage (1 hour)
#### Course Path
- [JS Info: Data storage in browsers](https://javascript.info/data-storage)


## AJC: Other environments like NodeJS (npm), YARN (1 hour)
#### Course Path
- [npm](https://thecodebarbarian.com/an-introduction-to-npm)
- [Yarn](https://medium.com/@jpblancoder/yarn-all-the-things-67a5b9839152)

## ADE Assignment: Javascript pagination (before week-2 of sprint 3 starts)
#### Problem Statement
##### Task 1
Apply what you learnt from [Introduction to babel & javascript bundlers](https://medium.com/backticks-tildes/introduction-to-babel-and-javascript-bundlers-fe6165de197c) to create a project that can understand ES6 and write the code for this assignment in ES6.

Make an API call to [https://jsonplaceholder.typicode.com/comments](https://jsonplaceholder.typicode.com/comments). An example for making an API [https://jsonplaceholder.typicode.com/](https://jsonplaceholder.typicode.com/)

You should receive a certain number of comments in an array.

##### Task 2
The API should give you 500 comments. But, imagine if the count was even higher. It's not wise to render so many comments on the screen at once. Your task is to divide the data in a group of 10 and show only 10 comments at a time on screen.

So, the data will be divided in pages as you see when you Google search. So, if there are 100 comments and the comments have to be grouped by 10, then we have 1 - 10 comments in page 1, 11 - 20 comments in page, 21 - 30 comments in page 3 and so on.

Render all the page links from **1 to n** based on the response as show in [https://i.stack.imgur.com/arvaT.png](https://i.stack.imgur.com/arvaT.png). Remember that there should be a group of 10 on each page.

Above the pagination, render the comments received from response in vertical. The list should change on page change.

##### Task 3
Active page button should be styled differently

##### Task 4
Create the next and previous link around page to move to next and previous page

##### Task 5
Finally generate a select element (dropdown) with a number of pages as input and update the recordset when the user changes the number. Say user choose page 5, then the list should show the comments from page 5

#### Input
Comments from [https://jsonplaceholder.typicode.com/comments](https://jsonplaceholder.typicode.com/comments)

#### Output
Pagination similar to [https://i.stack.imgur.com/arvaT.png](https://i.stack.imgur.com/arvaT.png)

#### Constraints
- Use async/await
- Try to persist the value (localStorage) to show the stale list in case API fails or internet is off.
