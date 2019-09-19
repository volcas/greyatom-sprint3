# Day 4

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
