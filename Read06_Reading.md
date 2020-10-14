##  Object Literals

### Objects group together a set of variables and functions to create a model of something you would recognize from the real world.  In an object, variables and functions take on new names.

- In an object, variables become known as properties.  
  - Properties tell us about the object.

- In an object, functions become known as methods. 
  - Methods represent tasks that are associated with the object. 

- Like variables and named functions, properties and methods have a name and a value.  In an object, that name is called a key

### Programmers use a lot of names/value pairs:

- HTML uses attribute names and values.
- CSS uses property names and values.

### In JavaScript:

- Variables have a name and you can assign them a value of a string, number, or Boolean.

- Arrays have a name and a group of values. (Each item in an array is a name/value pair because3 it has an index number and a value)

-Named functions have a name and value that is a set of statements to run if the function is called. 

-Objects consist of a set of name/value pairs (but the names are referred to as keys).

> Creating an object:
> Literal Notation

> The object is the curly braces and their contents. 
> The object is stored in a variable.

####  PROPERTIES
> `var object {`
>     `KEY: 'VALUE',`
>     `KEY: 'VALUE',`
>     `KEY: 'VALUE',`
> `}`
####  METHOD 
> `KEY: function() {`
>   `return this. Key -+<> this.Key;`
> `}`
> `};`

> When setting properties, treat the values like you would do for variables:  strings live in quotes and arrays live in square brackets. 

##  Accessing an object and dot notation.
You access the properties or methods of an object using dot notation.  You can also access properties using square brackets. 

To access a property or method of an object you use the name of the object, followed by a period, then the name of the property or method you want to access.  This is known as dot notation.

The period is known as the member operator.  The property or method on its right is a member of the object on its left.  

`var hotelName = hotel (which is the object).name; (which is the property/method name)
The . (dot) is the member operator.

You can also access the properties or methods of an object using square bracket syntax. 

This notation is most commonly used when:
* The name of the property or method contains special characters (such as a dash)
* The name of the property is a number (technically allowed, but should generally be avoided)
* A variable is being used in place of the property name (you will see this technique used in Chapter 12).



## Chapter 5 - Document Object Model (DOM)

The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules.  It is implemented by all major browser makers, and covers two primary areas; The making a model of the HTML page and Accessing and changing the HTML Page. 

* The DOM Tree is a model of a web page. 

* The browser represents the page using a DOM tree.
* DOM trees have four types of nodes:  document nodes, element nodes, attribute nodes, and text nodes.
* You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.
* Whenever a DOM query can return more than one node, it will always return a NodeList.
* From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.
* An element node can contain multiple text nodes and child elements that are siblings of each other.
* In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery)/
* Browsers offer tools for viewing the DOM tree. 



