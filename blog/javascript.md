### Analogy to describe Javascript and its relationship to HTML and CSS

HTML is the skeleton of the webpage, laying out the structure and creates a (pun intended) bare-bones
shape for the webpage.

CSS is the flashy exterior, affecting the colours, shapes, and overall layout of the page.

Javascript adds functionality and interactivity to the webpage. Through javascript, elements move, change,
and interact with hidden orders behind the scene.

To better imagine how these three work in concert, a good analogy would be the human body: HTML is the bones,
CSS is the body-type, weight, hair, eye-colour etc., and Javascript is the brain and tendons, allowing the
body to move and change.

### Explain 'control flow' and 'loops' using an example process from everdaylife, for example 'waking up' or 'brushing your teeth'

Control flow, simply, is the order in which the computer executes statements in a script. The code is run in order from the first
line in the file to the last line, unless this is affected by structures that change this flow, such as conditionals and loops.

An example to better articulate this would be to imagine control flow as the passage of time from when we wake in the morning, to
when we sleep at night. Conditionals such as "if" and "else" would be used for hunger, thirst, showering, and exercise. If we are
hungry, we should eat. Otherwise, we shouldn't eat. These conditionals are, funnily enough, conditional on something being true
or not.

A loop, meanwhile, is a little more complicated. Unlike a simple binary decision, a loop is a sequence of instructions that are
repeated until a certain condition is met. As a student, we could imagine a loop in our daily lives being to check whether our
assignments for that day have been completed, and if not, undergo all the required work until they are. This would then repeat
each day as long as there is work to be done. Another analogy would be to tidy our living areas if it had reached a threshold
of being too dirty/cluttered.

### Describe what the DOM is and an example of how you might interact with it.

The Document Object Model, or DOM for short, is the data representation of the objects that make up the structure and content of
a webpage document. The easiest way to interact with and view the DOM is to Right Click any webpage and select 'inspect', followed
by selecting the 'Console' view.

From this Console view, we can write javascript functions to affect the rest of the webpage (Only temporarily, a refresh will remove
and changed made). However, as a programmer using javascript, this view is most useful while writing a script; as a back-end language,
it can be difficult to see if functions are working as they should. Therefore, using a console.log() to check if our code is actually
creating change is a quick and easy way to avoid accidentally writing bad code that isn't properly connected to the HTML document.

### Explain the difference between accessing data from 'arrays' and 'objects'.

Arrays and Objects are both used to store collections of data in javascript. The difference lies in how they each store this data.

Arrays store data in consecutive memory locations, which is a fancy way of saying each item is numbered, starting at 0. Arrays are
useful when the items we wish to store have only one value, or that the order in which they are numbered also matters.

Objects store data in key-value pairs, so each key may hold more than one node of data. Objects are very useful when we need to assign
more than one value to each item. During the creation of our Javascript cafe, each item on the menu is an object, with that item's
stock and cost linked to each object.

### Explain what 'functions' are and why they are helpful.

A function is a code snippet that can be called by other code or itself. Arguments (values) are passed through the function as inputs,
from which the function returns outputs. Personally, trying to explain functions without a visual aid is difficult, so by looking at
the image below, I hope you can understand what I mean: