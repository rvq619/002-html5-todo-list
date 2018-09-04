# 002-html5-todo-list

Back to basics with this HTML5 todo list. 

Technologies used:
- HTML5
- Vanilla CSS3
- Vanilla Javascript

Files uploaded description:
- index000.html
- index001.html

Lessons Learned:
Contenteditable:
- Makes any page area editable in the browser.
- Single attribute: contenteditable:
	- contenteditable = "true"
	- contenteditable = "false"
	- contenteditable
	- contenteditable = "inherit"
- Browser support is off the charts:
	- see caniuse.com under "contenteditable"

Drag and drop:
- HTML5 attribute:
- JavaScript API.
- JavaScript events:
	- drag();
	- dragend();
	- dragenter();
	- dragexit();
	- dragleave();
	- dragover();
	- dragstart();
	- drop();
- Key related object:
	- dataTransfer:
		- set in dragstart() event.
		- read in drop().


localStorage:
- Very straightforward to use.
- Adds "state" to websites without server-side coding.
- Unlike cookie, stored in browser.
- 5MB limit vs. 4Kb for cookie.
- Name/value pair structure.
	- string only.
- Two simple commands:
	- localStorage.setItem("itemName", "itemValue");
	- localStorage.getItem("itemName");
- Really good browser support.
	- see caniuse.com under "web storage".
