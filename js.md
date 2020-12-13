

### DOM
#### dom document
- document
  - body
    //EX body.style.backgroundColor = "yellow";
  - forms //The forms collection returns a collection of all <form> elements in the document.
  - createAttribute("class"); 
  - createElement("Button");
  - getElementById("demo");
  - getElementsByClassName("example");
  - getElementsByName("fname");
  - getElementsByTagName("li");
  - querySelector(".example");
  - querySelectorAll(".example");
  - document.addEventListener("clickEvent", function(){
    document.getElementById("demo").innerHTML = "Hello World";
    
#### dom element
- element
	- .appendChild(node); 
	- .attributes;
	- .blur();
	- .childNodes
	- .children
	- .classList
		+ ex document.getElementById("myDIV").classList.add("mystyle");
	- .className
		- ex document.getElementById("myDIV").className = "mystyle";
	- .click()
		- ex document.getElementById("myCheck").click(); // Click on the checkbox
	- .closest(selector)
		- ex document.getElementById("myElement").closest(".container").style.border = "10px solid yellow";
	- .contains(span);
		- ex document.getElementById("myDIV").contains(spanElem);
	- .firstChild
		- ex document.getElementById("myList").firstChild.innerHTML;
	- .firstElementChild
		- ex document.getElementById("myList").firstElementChild.innerHTML;
	- .focus()
	- .getAttribute("class");
		- ex document.getElementsByTagName("H1")[0].getAttribute("class");
	- .getAttributeNode("class")
		- ex elmnt.getAttributeNode("class").value;
	- .getElementsByClassName("child")
		- ex element.getElementsByClassName("child")[0].innerHTML = "Milk";
	- .getElementsByTagName("ul")
	- .hasAttribute("onclick")
	- .hasAttributes()
	- .hasChildNodes();
	- .id
		- ex document.getElementById("demo").id = "newid";
	- .innerHTML
	- .innerText
	- .insertAdjacentElement("afterend", myDivElem);
	- .insertAdjacentHTML("afterend", "< p >My new paragraph</ p >");
	- .insertAdjacentText("afterend", "My inserted text");
	- .insertBefore	// method inserts a node as a child, right before an existing child, which you specify.
	- .isContentEditable;
	- .isEqualNode(item2);
	- .isSameNode(item2);
	- .lastChild
		- ex document.getElementById("myList").lastChild.innerHTML
	- .lastElementChild
		- ex document.getElementById("myList").lastElementChild.innerHTML;
	- .nextSibling
		- ex getElementById("item1").nextSibling.innerHTML;
	- .nextElementSibling
		- ex document.getElementById("item1").nextElementSibling.innerHTML;
