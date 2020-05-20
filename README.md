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

Finding HTML Objects. Refer to :https://www.w3schools.com/js/js_htmldom_document.asp under <em>Finding HTML Objects</em> section.

# Finding HTML Elements
There are several ways to find elements:
- by id
    - document.getElementById(id);
- by tag name
    - document.getElementsByTagName(tag);
- by class name
    - document.getElementsByClassName(class);
- by CSS selectors
    - document.querySelectorAll(selector);
- by HTML object collections

# Changing HTML
The HTML DOM allows Javascript to change the content of HTML elements

To create HTML content
```javascript
 document.write(content);
```

To change HTML content use the innerHTML property.
```javascript
document.getElementById(id).innerHTML = new HTML;
```

To change the value of an attribute use:
```javascript
document.getElementById(id).attribute = new value;
```

# Changing HTML Style
To change the style of an HTML element use:
```javascript
document.getElementById(id).style.property = new style;
```

# DOM Events/EventListener
Examples of HTML events:
- When user clicks
- When webpage loads
- When image loads
- When mouse hovers
- When input field changes
- When HTML form is submitted
- When user strokes key

The <b>addEventListener()</b> method attaches an event handler to the specified element. The syntax is:

element.addEventListener( String event, Function function, boolean useCapture(Optional));

In a situation when you have tags that are nested.
- <em>bubbling</em> handles inner most element's event first then proceeds outwards
- <em>capturing</em> handles out most element's event then proceeds inwards

To remove event listeners use:

element.removeEventListener(event, function)

# DOM Navigation
