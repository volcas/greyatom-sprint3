## Assignment: Javascript pagination
### Problem Statement
##### Task 1
We have provided you with required boilerplate to build this project.

Make an API call to [https://jsonplaceholder.typicode.com/comments](https://jsonplaceholder.typicode.com/comments). An example for making an API call [https://jsonplaceholder.typicode.com/](https://jsonplaceholder.typicode.com/)

You should receive a certain number of comments in an array.

##### Task 2
The API should give you 500 comments. But, imagine if the count was even higher. It's not wise to render so many comments on the screen at once. Your task is to divide the data in a group of 10 and show only 10 comments at a time on screen.

So, the data will be divided in pages. For example, on Google search, you see that since there are many site associated with search, they divide the results in pages.

If there are 100 comments and the comments have to be grouped by 10, then we have 1 - 10 comments in page 1, 11 - 20 comments in page 2, 21 - 30 comments in page 3 and so on.

Render all the page links from **1 to n** based on the response as shown in [https://i.stack.imgur.com/arvaT.png](https://i.stack.imgur.com/arvaT.png). Remember that there should be a group of 10 on each page.

Above the pagination, render the comments received from response in vertical. The list should change on page change.

##### Task 3
Active page button should be styled differently

##### Task 4
Create the next and previous link around page to move to next and previous page

##### Task 5
Finally create an input to enter the page number and update the recordset when the user changes the number. Say user enters page 5, then the list should show the comments from page 5.

Current page, should always be updated in the input.

#### Input
Comments from [https://jsonplaceholder.typicode.com/comments](https://jsonplaceholder.typicode.com/comments)

#### Output
Pagination should look similar to this (pagination image)(https://www.sketchappsources.com/resources/source-image/pagination-sudheer.png)

#### Constraints
- Use async/await
- Try to persist the value (localStorage) to show the stale list in case API fails or internet is off.
