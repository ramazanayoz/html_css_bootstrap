

## DOM
### dom document
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
    
### dom element
- element
	- .childNodes
	- .children
	- .classList
		//EX document.getElementById("myDIV").classList.add("mystyle");
	- .className
		//EX document.getElementById("myDIV").className = "mystyle";
	- .firstChild .firstElementChild
		//ex document.getElementById("myList").firstChild.innerHTML;
	- .innerHTML
	- .innerText
	- .id
		//ex document.getElementById("demo").id = "newid";
	- .insertBefore	// method inserts a node as a child, right before an existing child, which you specify.
	- .isContentEditable;
	- .lastChild, lastElementChild
		//ex document.getElementById("myList").lastChild.innerHTML
	- .nextSibling, nextElementSibling
		//ex getElementById("item1").nextSibling.innerHTML;
	- .outerHTML
		//Ex document.getElementsByTagName("h1").outerHTML = "< h3 >Header Changed!< / h3 >";
	- .outerText
		//EX document.getElementById("myH1").outerText = "Changed content!";
	- .parentNode, parentElement
		//EX document.getElementById("myLI").parentNode.nodeName;
	- .previousSibling, previousElementSibling
		//EX document.getElementById("item2").previousSibling.innerHTML;
	- .attributes;
	----------------------------------
	- .getElementsByClassName("child")
		//ex element.getElementsByClassName("child")[0].innerHTML = "Milk";
	- .getElementsByTagName("ul")
	- .querySelector(CSS selectors)
		//EX document.getElementById("myDIV").querySelector("p").innerHTML = "Hello World!";
	- .querySelectorAll(CSS selectors)
		//EX document.getElementById("myDIV").querySelectorAll(".example"); 
	--------------------------------------	
	- .appendChild(node); 
	- .insertAdjacentElement("afterend", myDivElem);
	- .insertAdjacentHTML("afterend", "< p >My new paragraph< / p >  ");
	- .insertAdjacentText("afterend", "My inserted text");
	- .closest(selector)
		//ex document.getElementById("myElement").closest(".container").style.border = "10px solid yellow";
	-----------------------------------------
	- .normalize()
		//ex document.getElementById("demo").normalize();
	- .remove();
		//EX document.getElementById("demo").remove();
	- .removeChild(childNode)
		//EX document.getElementById("myList").removeChild(list.childNodes[0]); 
	- .replaceChild(replacedNode, newNode)
	- .removeEventListener(..)
		//ex document.getElementById("myDIV").removeEventListener("mousemove", myFunction);		
	---------------------------------------------
	- .blur();
	- .click()
		//ex document.getElementById("myCheck").click(); // Click on the checkbox
	- .focus()
	------------------------------------------------
	- .contains(span);
		//ex document.getElementById("myDIV").contains(spanElem);
	- .isEqualNode(item2);
	- .isSameNode(item2);
	- .hasChildNodes();
	------------------------------------------------
	- .hasAttribute("onclick")
	- .hasAttributes()
	- .setAttribute("style", "background-color: red;");  
	- .setAttributeNode(..)
	- .getAttribute("class");
		//ex document.getElementsByTagName("H1")[0].getAttribute("class");
	- .getAttributeNode("class")
		//ex elmnt.getAttributeNode("class").value;
	- .removeAttribute('class'), removeAttributeNode
		//EX document.getElementsByTagName("H1")[0].removeAttribute("class");
