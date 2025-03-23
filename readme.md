01.
In JavaScript, an event refers to an occurrence that can be detected and responded to by the browser or JavaScript environment. Events are usually triggered by user actions such as clicking a button, typing in a text field, hovering over an element, or other interactions with a webpage.

 example,

click: Triggered when an element is clicked.
keydown: Triggered when a key is pressed down.
mouseover: Triggered when the mouse pointer enters an element.
submit: Triggered when a form is submitted.


02.
1.click: Triggered when an element is clicked.
2.dblclick: Triggered when an element is double-clicked.
3.mouseover: Triggered when the mouse pointer enters an element.
4.mouseout: Triggered when the mouse pointer leaves an element.
5.submit: Triggered when a form is submitted.
6.scroll: Triggered when an element or the window is scrolled.

03.
example code

 <button onclick="sayHello()">Click me!</button>

  <script>
    function sayHello() {
      alert("Hello, world!");
    }
  </script>

  04.

onclick
1.Set inline in HTML (<button onclick="...">)
2.Can only have one handler
3.Cannot remove directly from HTML

addEventListener()
1.Set via JavaScript (element.addEventListener())
2.Can have multiple handlers for the same event
3.Can easily remove using removeEventListener()

