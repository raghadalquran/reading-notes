# SUMMARY #
## Duckett HTML book ##

### Chpter 2 ###
#### Text ####
- HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs).
- They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).
- When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.
- Some of tags: <p> , <b> , <i> , <sup> , <br /> , <hr /> .
*Content management systems and HTML editors such as Dreamweaver usually have two views of the page you are creating: a visual editor and a code view.*
 - Visual editors often resemble word processors. Although each editor will differ slightly, there are some features that are common to most editors that allow you to control the presentation of text.
- Code views show you the code created by the visual editor so you can manually edit it, or so you can just enter new code yourself. 
- Some of semantic markup: <strong> , <em> , <blockquote> , <q> .


### Chapter 10 ###
#### Introducing CSS ####
- CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
- CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.
- Different versions of css & browser quirks
1. CSS1 was released in 1996 
2. CSS2 followed two years later.
3. Work on CSS3 has been ongoing but the major browsers have already started to implement it.
- Different types of selectors allow you to target your  X rules at different elements.
- Declarations are made up of two parts: the properties  X of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.
- CSS rules usually appear in a separate document,  X although they may appear within an HTML page.


 
## JAVASCRIPT ##

### Chpter 2 ###
- A script is made up of a series of statements. Each statement is like a step in a recipe. 
- Scripts contain very precise instructions. For example, 
you might specify that a value must be remembered before creating a calculation using that value. 
- Variables are used to temporarily store pieces of information used in the script. 
- Arrays are special types of variables that store more than one piece of related information. 
- JavaScript distinguishes between numbers (0-9), 
strings (text), and Boolean values (true or false). 
- Expressions evaluate into a single value.
- Expressions rely on operators to calculate a value. 

### Chapter 10 ###
- To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.
- The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.
- Each time a script enters a new execution context, there are two phases of activity: 
1. PREPARE.
2. 2: EXECUTE.
- In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.
- If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. 
- Error objects can help you find where your mistakes are and browsers have tools to help you read them.
- Now that you know what an error is and how the browser treats them, there are two things you can do with the errors. 
1. DEBUG THE SCRIPT TO FIX ERRORS.
2. HANDLE ERRORS GRACEFULLY.
- Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues. 
- The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. 
- The JavaScript console is just one of several developer tools that are found in all modern browsers. 
- If you know your code might fail, use try, catch, and finally. Each one is given its own code block. 
- If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them.
