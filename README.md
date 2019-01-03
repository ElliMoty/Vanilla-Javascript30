# JavaScript30

> Course created by [Wes Bos](https://github.com/wesbos). Join the challenge (for free!) here - [JavaScript30](https://javascript30.com/account)

<h1 align="center">
  <img src="https://javascript30.com/images/JS3-social-share.png" style="max-width:100%" alt="JavaScript30" />
</h1>

This repository is created to keep track of my progress in JavaScript30 and share whatever I am learning from each project with everyone who is interested. 

---

## My daily projects

### Project 1: 25 Dec 2018

**lesson1:** Learned some methods in vanilla Js! - data attributes, key event, keyCodes, `transitionend` event.

**handy pages:** Nice tool for finding JavaScript event keyCodes at [keycode.info](http://keycode.info/). For passing this course you can have a look at [Palash Mondal](https://github.com/palashmon)'s page too.

**Demo:** My first project is [here](https://ellimoty.github.io/Vanilla-Javascript30/Project01-DrumKit/index.html).

---

### Project 2: 26 Dec 2018

**lesson2:** playing with some css styles like transition, transform-origin. How to use cubic-bezier.

**Demo:** My 2nd project is [here](https://ellimoty.github.io/Vanilla-Javascript30/Project02-JS.CSS.Clock/html/index.html).

---

### Project 3: 30 Dec 2018

**lesson3:** 
- `:root`: this selector will always select the document's top-most element in the document tree. In an HTML document the `html` element will always be the highest-level parent, so the behavior of `:root` is predictable.
- In CSS property names that are prefixed with `--`, like `--example-name`, represent *custom properties* that contain a value that can be used in other declarations using the `var()` function.
- `NodeList` objects are collections of nodes, usually returned by properties such as `Node.childNodes` and methods such as `document.querySelectorAll()`. It's like an array (but it isn't). Although NodeList is not an Array, it is possible to iterate over it with `forEach()`. It can also be converted to a real Array using `Array.from()`.
- `change`: this event is sent to an element when its value changes. This event is limited to `input` elements, `textarea` boxes and `select` elements.
- `data-name` attributes allow us to store extra information on standard, semantic HTML elements without other hacks such as non-standard attributes and extra properties on DOM.
- `dataset` is an object that contains all data attributes from that specific element.

**handy pages:** The following pages helped me to finish this project and increase my knowledge.
- [css-tricks](https://css-tricks.com)
- [MDN](https://developer.mozilla.org)
- [Stack Overflow](https://stackoverflow.com)
- [jQuery](https://api.jquery.com)

**Demo:** My third project is [here](https://ellimoty.github.io/Vanilla-Javascript30/Project03-CSSVariables/index.html).

--- 

### Project 4: 01 Jan 2018

**lesson4:**
- `filter` method creates an array filled with all array elements that pass a test (provided as a function. This method required a function to be run for each element in the array.
- `map` method: creates a new array with the results of calling a function for every array element. `map()` does not change the original array.
- `sort` method: sorts an array alphabetically - example code to sort birthDates in descend way by using numbers 1 and -1:
```
const oldestToYoungest = array.sort((a, b) => a.year > b.year ? -1 : 1);
```
- `reduce` method: (Love this method :grin:) reduces the array to a single value and executes a provided function for each value of the array (from left-to-right).
> It is one the most amazing methods in Javascript. That is it!
- `Array.from` method: returns an Array object from any object with a length property or an iterable object.
- `textContent`: gets the text content of an element.
**Note:** This property is similar to the `innerText` property, however there are some differences:
   1- `textContent` returns the text content of all elements, while `innerText` returns the content of all elements, except for `script` and `style` elements.
   2- `innerText` will not return the text of elements that are hidden with CSS (`textContent` will)

- `includes` method: determines whether a string contains the characters of a specified string and returns `true` if the string contains the characters, and `false` if not. This method is case sensitive!

**handy pages:** 
- [w3schools](https://www.w3schools.com)