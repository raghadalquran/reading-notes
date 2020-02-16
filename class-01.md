
# SUMMARY #
## Introduction ##
##### *How* websites are created ? #####
- All websites use HTML and CSS, but content management systems, blogging software, and e-commerce platforms often add a few more technologies into the mix.
##### *How* the web works ? #####
- When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.

## Chapter 1 ##
##### Structure #####
- In all kinds of documents, structure is very important in helping readers to understand the messages you are trying to convey and to navigate around the document.
So, in order to learn how to write web pages, it is very important to understand how to structure documents. 
##### Structuring word documents #####
- The use of headings and subheadings in any document often reflects a hierarchy of information. 
- On the right, you can see a simple document in Microsoft Word.
##### HTML stands for HyperText Markup Language.#####
- The HyperText part refers to the fact that HTML allows you to create links that allow visitors to move from one page to another quickly and easily. 
- A markup language allows you to annotate text, and these annotations provide additional meaning to the contents of a document. If you think of a web 
page, we add code around the original text we want to display and the browser then uses the code to display the page correctly. So the tags we add are the markup.
- HTML pages are text documents.
- HTML uses tags (characters that sit inside angled brackets) to give the information they surround special meaning.
- Tags are often referred to as elements.
- Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes the end.
- Opening tags can carry attributes, which tell us more about the content of that element.
- Attributes require a name and a value.
- To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.

## Chapter 8 ##
##### The Evolution of html #####
- HTML 4 released 1997
- XHTML 1.0 released 2000
- HTML5 released 2000
##### DOCTYPES #####
- Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included). 
##### Comments In HTML #####
- If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
<!-- comment goes here -->
- It is a good idea to add comments to your code because, no matter how familiar you are with the page at the time of writing it, when you come back to it later (or if someone else needs to look at the code), comments will make it much easier to understand.
##### ID Attribute #####
- Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page.
-  Its value should start with a letter or an underscore (not a number or any other character).
- It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).
- The id attribute is known as a global attribute because it can be used on any element.
##### Class Attribute #####
- Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page. 
##### Block Elements #####
- Some elements will always appear to start on a new line in the browser window. These are known as block level elements. 
- Examples of block elements are < h1 >, < p >, < ul >, and < li >.
##### Inline Elements #####
- Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.
- Examples of inline elements are <a>, <b>, <em>, and <img>.
##### Grouping text & elements in a block #####
- The <div> element allows you to group a set of elements together in one block-level box.
- The <span> element acts like an inline equivalent of the <div> element. It is used to either:
1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
2. Contain a number of inline elements.
- An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.
##### Information about your pages #####
- The <meta> element lives inside the <head> element and contains information about that web page.
##### Escape Characters #####
- There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets.)
- Therefore, if you want these characters to appear on your page you need to use what are termed "escape" characters (also known as escape codes or entity references). For example, to write a left angled bracket, you can use either &lt; or &#60;. For an ampersand, you can use either &amp; or &#38;.

## Chapter 17 ##
##### HTML5 Layout#####
- HTML5 introduces a new set of elements that allow you to divide up the parts of a page.The names of these elements indicate the kind of content you will find in them.They are still subject to change, but that has not stopped many web page authors using them already.
(headers & footers, navigation, articles, asides, section, heading groups, figures, sectioning elements )
- The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
- The new elements provide clearer code (compared with using multiple <div> elements).
- Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
- To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.

## Chapter 18 ##
- It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
- Site maps allow you to plan the structure of a site. 
- Wireframes allow you to organize the information that will need to go on each page.
- Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
- You can differentiate between pieces of information using size, color, and style. 
- You can use grouping and similarity to help simplify the information you present.

## JAVASCRIPT SUMMARY ##

## Introduction ##
#### How JAVASCRIPT makes web pages more interactive ? ####
1. ACCESS CONTENT 
You can use JavaScript to select any element, attribute, or text from an HTML page. For example: 
• Select the text inside all of the <hl> elements on a page • Select any elements that have a c 1 ass attribute with a value of note • Find out what was entered into a text input whose id attribute has a value of ema i 1 
2. MODIFY CONTENT 
You can use JavaScript to add elements, attributes, and text to the page, or remove them. For example: 
• Add a paragraph of text after the first <hl> element • Change the value of c 1 ass attributes to trigger new CSS rules for those elements • Change the size or position of an <i mg> element 
3. PROGRAM RULES 
You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page. For example: 
• A gallery script could check which image a user clicked on and display a larger version of that image. • A mortgage calculator could collect values from a form, perform a calculation, and display repayments. • An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (also known as the viewport). 
4. REACT TO EVENTS 
You can specify that a script should run when a specific event has occurred. For example, it could be run when: 
• A button is pressed 
• A link is clicked (or tapped) on 
• A cursor hovers over an element 
• Information is added to a form 
• An interval of time has passed 
• A web page has finished loading 

## Chapter 1 ##
#### What is a script and how do i create one ?####
- A script is a series of instructions that the computer can follow in order to achieve a goal. 
- Each time the script runs, it might only use a subset of all the instructions. 
- Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically. 
- To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help). 

#### How do computers fit in with the world around them ? ####
- Computers create models of the worid using data.
- The models use objects to represent physical things.
- Programmers can write code to say "when this events occurs,run that code".
- Web browser use HTML markup to create a model of the web page.
- To make web pages interactive,you write code that uses the browser's model of the web page.

**WEB BROWSERS ARE PROGRAMS BUILT USING OBJECTS**
**THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE**

#### How do i write a script for a web page ? ####
- It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension. 
- The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file). 
- If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created. 

