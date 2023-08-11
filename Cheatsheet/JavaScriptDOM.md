# JavaScript DOM Cheatsheet

| Accessing Elements           | Description                                                                |
| ---------------------------- | -------------------------------------------------------------------------- |
| getElementById(id)           | Returns the element with the specified id                                  |
| querySelector(selector)      | Returns the first element that matches the specified CSS selector          |
| querySelectorAll( selector)  | Returns a collection of all elements that match the specified CSS selector |
| getElementsByTagName(name)   | Returns a collection of elements with the specified tog name               |
| getElementsByClassName(name) | Returns a collection of elements with the specified class name             |

<br/>

| Event Listeners                      |                                                               |
| ------------------------------------ | ------------------------------------------------------------- |
| addEventListener(event, function)    | Adds an event listener to on element                          |
| removeEventListener(event, function) | Removes an event sterner to an element                        |
| preventDefault()                     | Prevents the default action of an event                       |
| target                               | Gets the element that the event is currently being handled by |

<br/>

| Create/Remove Elements         |                                                                           |
| ------------------------------ | ------------------------------------------------------------------------- |
| createElement(name)            | Creates a new element with the specified tag name                         |
| createTextNode(text)           | Creates a new text node with the specified text                           |
| appendChild(node)              | Adds a node to the end of the list of children of a specified parent node |
| removeChild(node)              | Removes a child node from a specified parent node                         |
| replaceChild(newNode, oldNode) | Replaces an old child node with a new node                                |

<br/>

| Mouse Events  | Triggers                                            |
| ------------- | --------------------------------------------------- |
| onclick       | When the element is clicked                         |
| ondblclick    | When the element is double-clicked                  |
| onmousedown   | When the mouse button is pressed down on on element |
| onmouseenter  | When the mouse pointer enters an element            |
| onmouseeleave | When the mouse pointer leaves an element            |
| onmousemove   | When the mouse pointer is moving over an element    |
| onmouseover   | When the mouse pointer is over an element           |
| onmouseout    | When the mouse pointer is moved out of on element   |
| anmouseup     | When the mouse button is released over an element   |

<br/>

| Modify Elements           |                                                                                              |
| ------------------------- | -------------------------------------------------------------------------------------------- |
| innerHTML                 | Set or returns the HTML content within an element                                            |
| outerHTML                 | Sets or returns the entire HTMI. content of an element                                       |
| textContent               | Sets or returns the text content of a specified node1                                        |
| style                     | sets the inline style of an element                                                          |
| getAttribute(name)        | Gets the value of an attribute for an element                                                |
| setAttribute(name, value) | Sets the value of an attribute for an element                                                |
| hasAttribute(name)        | Returns a boolean indicating if the element has the specified attribute removes an attribute |
| removeAttribute(name)     | Removes an attribute                                                                         |
| classList                 | Gets the class list of an element, can be used to add, remove, or toggle a class             |

<br/>

| Keyboard Events |                                              |
| --------------- | -------------------------------------------- |
| onkeydown       | When a key in pressed down                   |
| onkeypress      | When a key is pressed down and then released |
| onkeyup         | When a key is released                       |

<br/>

| Form Events |                                             |
| ----------- | ------------------------------------------- |
| onblur      | When a element loses focus                  |
| onchange    | When the content of an element changes      |
| onfocus     | When an element gets focus                  |
| onselect    | When a user selects some text in an element |
| onsubmit    | When a form is submitted                    |

<br/>

| Traversing the DOM tree |                                                        |
| ----------------------- | ------------------------------------------------------ |
| parentNode              | Returns the parent node of a specified node            |
| childNodes              | Returns a collection of a node's child nodes           |
| firstChild              | Returns the first child node of a specified node       |
| lastChild               | Returns the last child node of a specified node        |
| previousSibling         | Returns the previous sibling node of a specified node  |
| nextSibling             | Returns the next sibling node of a specified node      |
| insertBefore            | Inserts a new element before a specified child element |

<br/>

| Others Events |                                                         |
| ------------- | ------------------------------------------------------- |
| onload        | When an element finishes loading                        |
| onunload      | When an element is unloaded                             |
| onresize      | When the browser window is resized                      |
| onscroll      | When the user scrolls the webpage                       |
| oncontextmenu | When the right mouse button is clicked                  |
| onerror       | When an error occurs while loading on external resource |
