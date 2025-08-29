1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
   
   ans:
   a.getElementById("id") : selects one element by its ID.

b.getElementsByClassName("class") : selects all elements with that class .

c.querySelector("selector") → selects first matching element using any CSS selector.

d.querySelectorAll("selector") : selects all matching elements .

2. How do you **create and insert a new element into the DOM**?

   
   ans:
   const div = document.createElement("div"); // create
div.textContent = "Hello";
document.body.appendChild(div); // insert

   
3. What is **Event Bubbling** and how does it work?
   
   
   Event Bubbling is when an event on an element, like a click, automatically moves up to its parent elements. The event starts at the element you interact with and then goes up through its parent, grandparent, and so on, so multiple elements can respond to the same event from inside to outside.

4. What is **Event Delegation** in JavaScript? Why is it useful?

   ans:
   Event Delegation is when you put one event listener on a parent element to handle events on its child elements. It is useful because it **saves code**, **works faster**, and can handle elements that are added later.

5. What is the difference between **preventDefault() and stopPropagation()** methods?

   ans:
   preventDefault() stops the browser’s **default action** (like following a link).
stopPropagation() stops the event from **bubbling up** to parent elements.

