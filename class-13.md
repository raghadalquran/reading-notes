# SUMMARY #

### HTML5 Storage? ### 

- it’s a way for web pages to *store* named key/value pairs locally, within the client web browser. 
- From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it.
- If you want to keep track programmatically of when the storage area changes, you can trap the storage event.
- The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
- There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress.
- But with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. 
- Data is stored as strings. If you are storing something other than a string, you’ll need to coerce it yourself when you retrieve it.


![img](https://image.slidesharecdn.com/als2011html5-111201200004-phpapp01/95/html5-technology-past-present-and-future-42-728.jpg?cb=1322788876)
