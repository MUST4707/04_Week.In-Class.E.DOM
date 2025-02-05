
Introduction to the DOM (Document Object Model)
===============================================

What is the DOM?
----------------

The DOM (Document Object Model) is a programming interface for web documents. It represents the structure of an HTML document as a tree of objects. It allows scripts (JavaScript) to manipulate content, structure, and style dynamically.

Structure of the DOM
--------------------

The document is structured as a hierarchical tree. Each element (e.g., `<html>`, `<body>`, `<p>`) is a node in the tree. Nodes include elements, attributes, and text.

Interacting with the DOM using JavaScript
-----------------------------------------

*   **Selecting elements:** `document.getElementById()`, `document.querySelector()`
*   **Modifying content:** `.innerText`, `.innerHTML`, `.textContent`
*   **Changing styles:** `.style` property
*   **Adding event listeners:** `addEventListener()`

Example Code
------------

### HTML:

            <p id="myText">Original Text</p>


### JavaScript:

        document.getElementById("myText").innerText = "The text has been updated!";


Why is the DOM Important?
-------------------------

Enables interactive and dynamic webpages. Allows real-time content updates without reloading the page. Forms the foundation of modern web development with JavaScript frameworks.

