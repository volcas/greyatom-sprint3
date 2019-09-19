
## Sprint 3 - Foundations of JavaScript

### Overview

Congratulations on completing Sprint 2!  In sprint 3, you'll learn how to make your websites dynamic and interactive with JavaScript!

This course path will guide you in learning basic to advanced JavaScript. You'll solve problems, build features and create a stand-alone web applications.

### What will you learn?

After this sprint, you will have an understanding of
- What is JavaScript?
- Why do you need to learn Javascript?
- What are the core features of JavaScript?
- What are the advanced features of JavaScript?
- How to make API calls to server in JavaScript?
- What is ECMAScript 6 and how can you use it to build modern application?
- What are some common libraries being used in JavaScript?

### What will you build?
You will be building a responsive clone of the Instagram landing page as shown in the picture below by implementing the HTML, CSS and JavaScript concepts learned. You'll gain insights on building the frontend of a social media site and learning the small interactions such as liking a pic, adding a comment that come along with it.

![Instagram Clone](insta.png)


### Learning Outcomes
After this sprint, you will have an understanding of

**Basics of JS programming (BJSP)**
 - Variables and Data types
 - Operators
 - Control flow
 - Error handling
 - Functions
 - Object-oriented programming
 - Data structures
 - Basics of DOM and DOM Manipulation
 - Assignment

 **AJAX (Promises) & DOM Events (ADE)**
 - Fetch or HTTP request
 - Event loop - Synchronous and asynchronous
 - ES6 - Async await
 - Event delegation, propagation, bubbling
 - Using external libraries like jQuery, Lodash.
 - Assignment

**Advanced Javascript Concepts (AJC)**
 - Advanced data structure - arrays, objects (react specific topics)
 - How ES6 works - Babel
 - This keyword
 - Arrow functions
 - Template literal
 - Let and const
 - Import, export modules
 - Default parameters
 - Hashmap (optional)
 - Inheritance
 - Other environments like NodeJS (npm), YARN
 - Best Practices
 - Assignment

### Content Tree

| Concept | Week | Topic | Day | Difficulty Level | Estimated Time |
|--|--|--|--|--|--|
| Basics of JS programming (BJSP) | 1 |  |  |  |  |




## Day 1

### Basics of JS programming (BJSP): Intro  (10 min)
#### Overview
If you think of any web page you interact with today, JavaScript is most likely providing the action on the page. JavaScript can be used to change the status of a button when it is clicked on, create a chat window at the bottom of your screen, or even create a web-based game. With modern tools like [Node.js](https://nodejs.org/), JavaScript can now also be used to save data to a database or to create desktop applications. The applications are limitless, and we're excited to see what you'll create. Along with HTML and CSS, JavaScript is one of the three major tools you'll need to understand if you want to build a modern website.

From  [W3C](https://www.w3.org/community/webed/wiki/A_Short_History_of_JavaScript):

> JavaScript, not to be confused with Java, was created in 10 days in May 1995 by Brendan Eich, then working at Netscape and now of Mozilla. JavaScript was not always known as JavaScript: the original name was Mocha, a name chosen by Marc Andreessen, founder of Netscape. In September of 1995 the name was changed to LiveScript, then in December of the same year, upon receiving a trademark license from Sun, the name JavaScript was adopted. This was somewhat of a marketing move at the time, with Java being very popular around then.


#### Course Path
- [https://javascript.info/intro](https://javascript.info/intro)
- [What're the benefits of learning JavaScript?](https://boostlog.io/@sonuton/what-are-the-benefits-of-learning-javascript-5a87b3669837780090b3e833)


### BJSP: Variables and Data types (1 hour)
#### Course Path
- [JS Info: Variables](https://javascript.info/variables)
- [JS Info: String](https://javascript.info/string)
- [Javascript Is Sexy: JS Variable scope & hoisting](http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/)
- [JS Info: Types](https://javascript.info/types)
- [JS Info: Type conversions](https://javascript.info/type-conversions)
#### Additional References
- [MDN: Grammar and types](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_Types)


### BJSP: Operators (30 min)
#### Course Path
- [JS Info: Operators](https://javascript.info/operators)
- [Tutorial Republic: Javascript operators](https://www.tutorialrepublic.com/javascript-tutorial/javascript-operators.php)

#### Additional References
- [Tutorials Teacher: Javascript operators](https://www.tutorialsteacher.com/javascript/javascript-operators)
- Bit wise operators can be skipped as it's not quite heavily used in frontend unless the need arises. Just in case, if you are wondering about it's use case, please click on the [link](https://dev.to/puritanic/nsfw-use-cases-for-bitwise-operators-in-js-2om5)


### BJSP: Control flow and Error handling (30 min)
#### Course Path
- [JS Info: if else](https://javascript.info/ifelse)
- [JS Info: Switch](https://javascript.info/switch)
- [Tutorials Teacher: Javascript error handling](https://www.tutorialsteacher.com/javascript/javascript-error-handling)

#### Additional References
- [MDN: Control flow & error handling](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)
- [MDN: Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)


### BJSP: Loops (1 hour)
#### Course Path
- [JS Info: While-for](https://javascript.info/while-for)
- [Medium: The complete guide to loops](https://medium.com/@js_tut/the-complete-guide-to-loops-cfa6522157e9)

#### Additional References
- [MDN: Loops_and_iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
- [Tutorial Republic: JS loops](https://www.tutorialrepublic.com/javascript-tutorial/javascript-loops.php)


### BJSP: Functions (3 hours)
#### Course Path
- [JS Info: Function basics](https://javascript.info/function-basics)
- [Javascript Is Sexy: Understand JS closures with ease](https://javascriptissexy.com/understand-javascript-closures-with-ease/)
- [Codeburst: What the heck is a callback?](https://codeburst.io/javascript-what-the-heck-is-a-callback-aba4da2deced)
- [Tutorials Teacher: Immediately invoked function expression (iife)](https://www.tutorialsteacher.com/javascript/immediately-invoked-function-expression-iife)
- [JS Info: Recursion](https://javascript.info/recursion)
- [JS Info: Currying partials](https://javascript.info/currying-partials)

#### Additional References
- [MDN: Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
- [MDN: Callback function](https://developer.mozilla.org/en-US/docs/Glossary/Callback_function)


### BJSP: Object-oriented programming (2 hour)
#### Course Path
- [Object Playground](http://www.objectplayground.com/)
- [JS Info: Function object](https://javascript.info/function-object)
- [Javascript Is Sexy: Apply, call & bind methods](http://javascriptissexy.com/javascript-apply-call-and-bind-methods-are-essential-for-javascript-professionals/)

#### Additional References
- [JS Info: Object basics](https://javascript.info/object-basics)
- [JS Info: Object properties](https://javascript.info/object-properties)
- [JS Info: Prototypes](https://javascript.info/prototypes)


### BJSP: Data structures (2 hours)
#### Course Path
- [JS Info: Array Methods](https://javascript.info/array-methods)
- [Medium: Data structures in JS](https://medium.com/siliconwat/data-structures-in-javascript-1b9aed0ea17c)
- [Medium: Data structures in JS Part 1](https://blog.bitsrc.io/data-structures-in-javascript-part-1-8231c9a4bc8b)
- [Medium: Data structures in JS Part 2](https://blog.bitsrc.io/data-structures-in-javascript-part-2-d0d09b761df0)

## Day 2

### BJSP: Basics of DOM and DOM Manipulation (3 hour)
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


### BJSP: Debugging (30 min)
#### Course Path
- [Debugging techniques with Javascript](https://www.youtube.com/watch?v=3EXNtmgf87s)

#### Additional References
- [Debugging techniques with Javascript](https://www.youtube.com/watch?v=3EXNtmgf87s)
- [Googler Devs: Chrome devtools](https://developers.google.com/web/tools/chrome-devtools/javascript/)
- [JS debugging tips](https://raygun.com/javascript-debugging-tips)
- [JS Info: Debugging Chrome](https://javascript.info/debugging-chrome)


### BJSP Assignment: Remove Duplicate (2 hours)
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

### BJSP Assignment: Quiz (First Half) (3 hours)
#### Problem Statement
In your code, Create an array of Objects with 3 properties i.e question, answer, options e.g
> [
> &nbsp;&nbsp;{
> &nbsp;&nbsp;&nbsp;&nbsp;question: 'What is the capital of India?',
> &nbsp;&nbsp;&nbsp;&nbsp;answer: 'Delhi',
> &nbsp;&nbsp;&nbsp;&nbsp;options: [ 'Mumbai', 'Delhi', 'Gujarat' ]
> &nbsp;&nbsp;},
> &nbsp;&nbsp;{
> &nbsp;&nbsp;&nbsp;&nbsp;question: 'When did India win the first world cup?',
> &nbsp;&nbsp;&nbsp;&nbsp;answer: '1983',
> &nbsp;&nbsp;&nbsp;&nbsp;options: [ '1990', '1983', '2003' ]
> &nbsp;&nbsp;},
> ...so on
> ]

As shown in the example, create ten such objects with different questions, answers and options. Then design to create the site has been provided below.

![Quiz](quiz.png)

On answering the first question, the first question should slide out and the second question should slide in. The user should not be allowed to go to this next question until the first question is answered.

Once the user has answered all the question, show the list of questions with the answers provided by the user alongside the right answer. Sample can be seen in the image.

You can see a Exit button in the image which will allow the user to quit the quiz whenever he or she prefers. Once the user quits, the quiz should restart.

#### Input
[1, 9, 2, 3, 3, 3, 3, 3, 4, 4, 5, 6, 7, 8, 5, 6, 6, 9, 10, 10]

#### Output
[[1, 2, 3, 4, 5], [6, 7, 8, 9, 10]]

#### Constraints
- Not more than 20 questions.
- User should be allowed to exit.


## Day 3

### BJSP Assignment: Quiz (Second Half)  (4 hours)
...complete the assigment

### AJAX (Promises) & DOM Events (ADE): Intro (10 min)
#### Overview
**DOM (Document Object Model) events** are an actions that occurs as a result of the user action or as result of state change of the elements of a [DOM](https://en.wikipedia.org/wiki/Document_Object_Model) tree.

Examples of HTML DOM events:
-   When a user clicks the mouse
-   When a web page has loaded
-   When an image has been loaded
-   When the mouse moves over an element
-   When an input field is changed
-   When an HTML form is submitted
-   When a user strokes a key

AJAX (Asynchronous JavaScript and XML) is a mechanism through which web applications can send and retrieve data from a [server](https://en.wikipedia.org/wiki/Web_server "Web server") asynchronously (in the background) without interfering with the display and behavior of the existing page. By decoupling the data interchange layer from the presentation layer, Ajax allows web pages and, by extension, web applications, to change content dynamically without the need to reload the entire page. In practice, modern implementations commonly utilize [JSON](https://en.wikipedia.org/wiki/JSON "JSON") instead of XML.


### ADE: REST (1 hour)
#### Course Path
- [HTTP Explained: The HTTP Request Status Code Guide (Complete)](https://www.youtube.com/watch?v=VLH3FMQ5BIQ)
- [How HTTP Requests Work](https://www.youtube.com/watch?v=CFzgKfnmG-Q)

#### Additional References
- [HTTP Methods/](https://restfulapi.net/http-methods/)
- [REST API concepts and examples](https://www.youtube.com/watch?v=7YcW25PHnAA)


### ADE: AJAX and Promises (2 hours)
#### Course Path
- [What Is Ajax?](https://www.youtube.com/watch?v=3l13qGLTgNw)
- [JSON and AJAX Tutorial: With Real Examples](https://www.youtube.com/watch?v=rJesac0_Ftw)
- [JS Promises Explained](https://www.macadamian.com/learn/javascript-promises-explained/)

#### Additional References
- [MDN: AJAX](https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX/Getting_Started)

### ADE: Fetch API in JavaScript (1 hour)
#### Course Path
- [Fetch API introduction to promised based data fetching in plain javascript/](https://codingthesmartway.com/fetch-api-introduction-to-promised-based-data-fetching-in-plain-javascript/)


### ADE: Event loop (1 hour)
#### Course Path
- [What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- [JS timing events](https://www.w3schools.com/js/js_timing.asp)

#### Additional References
- [Understanding event loop call stack event job queue in JS](https://medium.com/@Rahulx1/understanding-event-loop-call-stack-event-job-queue-in-javascript-63dcd2c71ecd)
- [Event loop concurrency](https://www.applozic.com/blog/javascript%E2%80%8A-%E2%80%8Aevent-loop-concurrency/)



## Day 4

### ADE: Event delegation, propagation, bubbling (1 hour)
#### Course Path
-  [Event Propagation Explained (w Bubbling and Capturing)](https://www.youtube.com/watch?v=BtOrr7oTH_8)

#### Additional References
- [Event Propagation Explained (w Bubbling and Capturing)](https://www.youtube.com/watch?v=BtOrr7oTH_8)
- [Whats the difference between JS event delegation, bubbling and capturing?](https://gomakethings.com/whats-the-difference-between-javascript-event-delegation-bubbling-and-capturing/)
- [Handing JS events efficiently with bubble and capture](https://dev.to/shimphillip/handing-javascript-events-efficiently-with-bubble-and-capture-4ha5)


### ADE: Using external libraries like jQuery, Lodash (1 hour)
#### Course Path
-  [jQuery Crash Course](https://www.youtube.com/watch?v=hMxGhHNOkCU&list=PLoYCgNOIyGABdI2V8I_SWo22tFpgh2s6_)
- [Introduction to lodash](https://medium.com/front-end-weekly/introduction-to-lodash-71dbee093b49)

#### Additional References
- [jQuery](https://jquery.com/)
- [Lodash](https://lodash.com/)


### ADE: Best Practices (30 min)
#### Course Path
-  [https://code.tutsplus.com/tutorials/24-javascript-best-practices-for-beginners--net-5399](https://code.tutsplus.com/tutorials/24-javascript-best-practices-for-beginners--net-5399)
- [https://ilikekillnerds.com/2015/03/things-every-javascript-developer-should-know/](https://ilikekillnerds.com/2015/03/things-every-javascript-developer-should-know/)



### ADE Assignment: Auto Image Slider - First Half (5 hours 30 min)
#### Problem Statement
##### Task 1
Make a request using `fetch() API` to [https://jsonplaceholder.typicode.com/photos](https://jsonplaceholder.typicode.com/photos) to retrieve an array of photo detail objects. Click on the link to see the sample response. It should be an array of photo detail objects.

##### Task 2
In this response, you will see properties with the name **'title', 'url', 'thumbnailUrl', etc.** Reduce the **size of the response array** to the top five photo details.

##### Task 3
Create an animated image slider which auto slides in every 5 seconds using the **reduced response array**. The slider should look similar to the image provided in the link: [https://www.jqueryscript.net/images/Basic-Thumbnail-Image-Slider-Plugin-with-jQuery-Thumb-slider.jpg](https://www.jqueryscript.net/images/Basic-Thumbnail-Image-Slider-Plugin-with-jQuery-Thumb-slider.jpg)

Apply some random CSS animation of your choice on image slide in and out.

##### Task 4
Render the title, url and thumbnail url of the active slide under the Image Slider. On slide change, it should render the previously mentioned properties of the next active slide.

##### Task 5
User should be able to slide the images using the arrow keys (<- / ->). On using the navigational arrow keys, the auto slide should stop. The user should be given complete control.

#### Input
Photo details from [https://jsonplaceholder.typicode.com/photos](https://jsonplaceholder.typicode.com/photos) API.

#### Output
Animated Image Slider

#### Constraints
 - Use the `fetch()` API for API call.
 - Use jQuery for DOM manipulation
 - Use lodash once for any array/object manipulation.
 - Try to use as many features as you can from ES6 concepts you learnt


## Day 4
### ADE Assignment: Auto Image Slider - Second Half (3 hours)

### Advanced Javascript Concepts (AJC) : Intro
#### Overview
JavaScript is huge. Pat yourself at the back for having reached this far. The course was broken into the essentials and the advanced JS concepts being used by the Industry. In this section, we'll be exploring the Advanced concepts that simplifies JS and provides more power to the developer.

### AJC: Advanced data structure (1 hour)
#### Course Path
- [Codeburst: Useful JS array & object methods](https://codeburst.io/useful-javascript-array-and-object-methods-6c7971d93230)


### AJC: ES6 (2 hour)
#### Course Path
- Install Node.js [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
- [Introduction to babel & javascript bundlers](https://medium.com/backticks-tildes/introduction-to-babel-and-javascript-bundlers-fe6165de197c)
- [JavaScript ES6 Tutorial: Complete Playlist](https://www.youtube.com/watch?v=0Mp2kwE8xY0&list=PL4cUxeGkcC9gKfw25slm4CUDUcM_sXdml)
- [JavaScript Modules: ES6 Import and Export](https://www.youtube.com/watch?v=_3oSWwapPKQ&feature=youtu.be)

#### Additional References
- [MDN: ES6 Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
- [ES6 tutorial for beginners](https://codeburst.io/es6-tutorial-for-beginners-5f3c4e7960be)
- [What you should know about es6 maps?](https://hackernoon.com/what-you-should-know-about-es6-maps-dc66af6b9a1e)
- [https://babeljs.io/](https://babeljs.io/)
- [ES6 and Babel tutorial](https://html5hive.org/es6-and-babel-tutorial/)


### AJC: ES6 - Async await (1 hour)
#### Course Path
-  [Async JS Crash Course - Callbacks, Promises, Async Await](https://www.youtube.com/watch?v=PoRJizFvM7s)

#### Additional References
- [Async / Await in JavaScript - What, Why and How - Fun Fun Function](https://www.youtube.com/watch?v=568g8hxJJp4)
- [6 reasons why javascripts async await blows promises away](https://hackernoon.com/6-reasons-why-javascripts-async-await-blows-promises-away-tutorial-c7ec10518dd9)
- [Async JS from callbacks to promises to async-await/](https://tylermcginnis.com/async-javascript-from-callbacks-to-promises-to-async-await/)


### AJC: ES6 - Class Inheritance (1 hour)
#### Course Path
-  [JS Info: Class inheritance](https://javascript.info/class-inheritance)
- [ES6: Classes & Inheritance](https://medium.com/ecmascript-2015/es6-classes-and-inheritance-607804080906)


## Day 5

### AJC: 'this' keyword (1 hour)
#### Course Path
- [JS Info: Object Methods](https://javascript.info/object-methods)
- [Understanding the 'this' keyword in JS](https://medium.com/quick-code/understanding-the-this-keyword-in-javascript-cb76d4c7c5e8)


### AJC: Storage (1 hour)
#### Course Path
- [JS Info: Data storage in browsers](https://javascript.info/data-storage)


### AJC: Other environments like NodeJS (npm), YARN (1 hour)
#### Course Path
- [npm](https://thecodebarbarian.com/an-introduction-to-npm)
- [Yarn](https://medium.com/@jpblancoder/yarn-all-the-things-67a5b9839152)

### ADE Assignment: Javascript pagination (before week-2 of sprint 3)
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



## Project Tasks

**Objective**: Build a Instagram clone.
