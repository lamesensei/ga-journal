# Things I've learnt at General Assembly
###*Web Development Intensive*
### Day 1 / 2
* parseInt() for prompt() to eliminate any unwanted string concatenation for number values.
* Pressing cancel on a prompt() generates a NUll value.
* Need to work on 'cleaner' coding - **VARIABLE ALL THE THINGS**.
>Things were slow - but the assignment was fun.

### Day 3
* indexOf() used for string comparison. Note: return position of first instance found / meaning it can return '0' which is 'falsy'. Implement !== -1 to allow all search entries to go through.
* Look at other students pull requests and improved own code (assigning nested objects to variables to shorten code)
>Feeling good :)

### Day 4
* head -n 5 for printing specific lines of files in terminal
* switch case for multiple similar if/else conditionals

### Day 5
* setTimeout(function,1000) wrong vs setTimeout(function(),1000) right
* Function callbacks always involve the **function** and not its return value!

### Day 6/7
* Need to plan / pseudo code before starting.
* Focus on requirements.
>Assignment was fun but lost track creating function after function...

![shit](https://media.giphy.com/media/26tnnpcYVRNJGlHy0/giphy.gif)

### Day 8
* appendChild() moves existing reference - no need to removeChild()
* DOM element .style (for CSS) key is available without setAttribute
* Traverse down the children, but can also traverse from children to parents. (note to use parents more.)
* DOM lists can be pass into: 
```javascript
[].forEach.call(list, function(element) {/*do stuff with element here*/})
```
### Day 9
* Take note - most DOM get selectors usually return arrays which need to be [indexed].

> Algorithms zzzzzz

### Day 10
* Check for array using:
```javascript
Array.isArray(element) or element.constructor === false
```
* Perform code logic and DOM manipulation separately if possible!

* eg: Tic Tac Toe JS board and DOM board

### Day 11?

* Lost track of time...

### Day 12

* Take note of code logic if it fires during 'successful' response handler and also 'errored' responses

* XMLHttpRequest can be reused

### PROJECT??? - 19/09/18

* Sleep is important

* Segment code over multiple JS files for organization

* CSS (keyframe) animation is easy to implement. Timing control can be implemented via JS by setting the animation-name or other style keywords.

* Bootstrap might seem counterintuitive with its reliance on multiple classes - but it is really good.

* Try to minimize global variable usage and implement functions in such a way that it always returns something useful. 