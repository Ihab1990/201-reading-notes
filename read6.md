
## THE DOM TREE IS A MODEL OF A WEB PAGE
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes. 

Each node is an object with methods and properties.
Scripts access and update this DOM tree (not the source HTML file).
Any changes made to the DOM tree are reflected in the browser. 

Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes. 

DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes. 

When a DOM method can return more than one element, it returns a
Nodelist (even if it only finds one matching element). 


From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.

An element node can contain multiple text nodes and
child elements that are siblings of each other.

In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).

Browsers offer tools for viewing the DOM tree .
