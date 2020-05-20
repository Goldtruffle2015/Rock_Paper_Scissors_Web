# What is the HTML DOM?
It is a way to modify html elements.

# Methods 
HTML DOM methods are <b>actions</b> you can perform

HTML DOM properties are <b>values</b> that you can set or change

Methods include:
- getElementById()
    - accesses HTML elements
- innerHTML Property
    - access the content of the element

# JavsScript HTML DOM Document
The document object represents your web page. To access elements you start by accessing the document object ("document").

Finding HTML Elements:
- document.getElementById(id)
    - Find an element by element id
- document.getElementsByTagName(name)
    - Find elements by tag name
- document.getElementsByClassName(name)
    - Find elements by class name

Changing HTML elements:
- element.innerHTML = new html content
    - Change the inner HTML of an element
- element.attribute = new value
    - Change the attribute value of an HTML element
- element.style.property = new style
    - Chagne the style of an HTML element
- element.setAttribute(attribute, value)
    - Change the attribute value of an HTML element

Adding and Deleting Elements:
- document.createElement(element)
    - Create an HTML element
- document.removeChild(element)
    - Remove an HTML element
- document.appendChild(element)
    - Add an HTML element
- document.replaceChild(new, old)
    - Replace an HTML element
- document.write(text)
    - Write into the HTML output stream

Adding Events Handlers:
- Document.getElementById(id).onclick = function(){code}
    - Adding event handler code to an onclick event