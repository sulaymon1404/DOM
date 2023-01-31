# DOM

## Dom
## With the HTML DOM, JavaScript can access and change all the elements of an HTML document.
# The backbone of an HTML document is tags.According to the Document ObjectModel (DOM), every HTML tag is anobject. Nested tags are “children” ofthe enclosing one. The text inside a tag is an object as well.

# The HTML DOM (Document Object Model)
![](/Images/1.PNG)

## With the object model, JavaScript gets all the power it needs to create dynamic HTML:
- JavaScript can change all the HTML elements in the page
- JavaScript can change all the HTML attributes in the page
- JavaScript can change all the CSS styles in the page
- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page




# What is the HTML DOM?
# The HTML DOM is a standard object model and programming interface for HTML. It defines:

- The HTML elements as objects
- The properties of all HTML elements
- The methods to access all HTML elements
- The events for all HTML elements

# In other words: The HTML DOM is a standard for how to get, change, add, or delete HTML elements.


# DOM - Searching: Styles and classes
# Before we get into JavaScript’s ways of dealing with styles and classes –here’s an important rule. Hopefully it’s obvious enough, but we still have to mention it.
- There are generally two ways to style an element:
-Create a class in CSS and add it: <div class="...">
- Write properties directly into style: <div style="...">.
- JavaScript can modify both classes and style properties.


# DOM - Searching: Styles and classes

# Changing a class is one of the most frequently used actions in scripts.
# In the ancient time, there was a limitation in JavaScript: a reserved word like "class" could not be an object property.
# That limitation does not exist now, but at that time it was impossible to have a "class" property, like elem.class.So for classes the similar-looking property "className" was introduced: the elem.className corresponds to the "class" attribute.

# The HTML DOM Document Object
# The document object represents your web page.

# If you want to access any element in an HTML page, you always start with accessing the document object.

# Below are some examples of how you can use the document object to access and manipulate HTML.
![](/Images/2.PNG)
![](/Images/3.PNG)
![](/Images/4.PNG)

# JavaScript Form Validation

# HTML form validation can be done by JavaScript.

# If a form field (fname) is empty, this function alerts a message, and returns false, to prevent the form from being submitted:

![](/Images/5.PNG)