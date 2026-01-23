Assignment 1 - Hello World: GitHub and d3  
===

Link to gh-pages site: https://hsmith1212.github.io/a1-ghd3/ 

My Visualization
==
For this assignment, I created a visualization including a stoplight and car. The stoplight is made of a rectangle, three circles, and a line. The car is a piece of clipart I found online and cited below. Additionally, I put two tire images over the car, also cited below. An image of the visualization before any interaction is below.

<img width="1341" height="862" alt="image" src="https://github.com/user-attachments/assets/63d4707f-d8a0-465f-9d6e-39a874bcfd6d" />

The visualization responds to user interaction as well. Any of the three stoplights can be clicked, and in response, a word next to each of the stoplights will appear: "Go!" when green is clicked, "Slow Down!" when yellow is clicked, and "Stop!" when red is clicked. At the same time, the rotation speed of the tires will change if the clicked light is different than the previously clicked one. Hitting red will stop any rotation, hitting yellow will set them to a slow rotation, and hitting green will set them to a steady rotation. A video of this animation is below.

https://github.com/user-attachments/assets/8479501a-43d0-457c-a119-7d54c4df86d8

Technical Achievements
=

My biggest technial achievement included my use of animation in my visualization. I had to do research into how to keep the animation constantly running, not just call transform one time on the tires. My tires are constantly being animated using the timer function from d3. I learned how to change the speed of this animation using event listeners on the stoplights. 
Another technical achievement of mine is my use of an array to create the circles of the stoplight. Rather than manually creating three different circles, I made an array of circles and joins to create all three circles in one section of my code.

Design Achievements
=

1. Created a recognizeable stop light out of simple shapes
2. Used overlapping clipart images to make it look like the wheels of the tire rotate
3. The stoplight is interactive, causing text to appear and a change in the rotation of the wheels depending on which is clicked
4. The tires turn as in the direction of the stoplight, appearing like the car's driving is reacting directly to the stoplight

Sources for Coding Assistance
=
* https://observablehq.com/@nyuvis/d3-introduction
  * This was the first source I consulted, and where I was inspired to do the array of circles. I used the code here to learn how to display an array of svg shapes. I edited the code to be three circles vertically stacked, with different colors, to repersent a traffic light.
* https://www.w3schools.com/js/js_arrays.asp 
  * The first source did not describe how to actually make an array in JavaScript, so I learned how to here.
* [https://developer.mozilla.org/en-US/docs/Web/SVG/Reference/Element/circle](https://developer.mozilla.org/en-US/docs/Web/SVG/Reference)
  * I used the elements and attributes lists in this documentation to create each of my svg elements: circles, a rectangle, a line, and images. I also used it to learn the transform attribute and rotate my tires. 
* https://d3js.org/d3-selection/events and https://d3js.org/d3-timer
  * I used this d3 documentation to create my animation.
* https://github.com/mrdbourke/pytorch-deep-learning/discussions/530
  * This showed me how to get my images I uploaded to GitHub into my actual code. 

Image Sources
=
* Car: https://www.freepik.com/free-vector/red-sedan-car-cartoon-style-isolated-white-background_18212304.htm#fromView=keyword&page=1&position=1&uuid=dda10481-31f4-44ff-a5d7-3de7ad8ffda7&query=Simple+car+clipart
* Tire: https://creazilla.com/media/clipart/23311/simple-car-wheel-tire-side-view 
