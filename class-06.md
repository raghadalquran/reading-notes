# SUMMARY #

## Chapter 3: “Object Literals” ##
- Objects group together a set of variables and functions to create a model of a something you would recognize from the real world.
- In an object, variables and functions take on new names. 
- If a variable is part of an object, it is called a property. Properties tell us about the object.
- If a function is part of an object, it is called a method. 
- Methods represent tasks that are as Programmers use a lot of name/value pairs:
+ HTML uses attribute names and values. - CSS uses property names and values. 
### In JavaScript: ### 
+ Variables have a name and you can assign them a value of a string, number, or Boolean.
+ Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.)
+ Named functions have a name and value that is a set of statements to run if the function is called.
+ Objects consist of a set of name/value pairs (but the names are referred to as keys). sociated with the object.

## Chapter 5: “Document Object Model” ##

- As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. 
- DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes. 
- You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. 
- Accessing and updating the **DOM tree** involves two steps:
1. Locate the node that represents the element you want to work with. 
2. Use its text content, child elements, and attributes. 
- From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques. 
- An element node can contain multiple text nodes and child elements that are siblings of each other. 
![dom_tree](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)
