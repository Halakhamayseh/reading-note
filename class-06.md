# Problem Domain, Objects, and the DOM

## Object
>  each physical thing in the world can be represented as an object. 

1. **Variable** is a part of Object
- IN AN OBJECT: VARIABLES BECOME KNOWN AS **PROPERTIES** .

2. **function** is a part of Object 
- IN AN OBJECT: FUNCTIONS BECOME KNOWN AS **METHODS**

+ Create an Object
> Literal notation is the easiest and most popular wat to create object


+ Accessing an object and **DOT** notation
> you can access the properties or method of an object using dot notation.
>> *Example for properties* ` var carName = car.name;`
>> *Example for method* ` var carMile = car.mile();`

> you can access the properties of an object *not its method* using **square bracket**
>> *Example* `var hotelName=hotel['name'];`


## DOM (Document Object Model)
> is a tree of Objects

>> When the browser loads a web page, it creates a model of the page in memory.

- The DOM is called an object model because the model (the DOM tree) is
made of objects. 

- Each object represents a different part of the page loaded in the browser window
 

- THE DOM TREE 
>>IS A MODEL OF A WEB PAGE

- >>  Any changes made to the DOM tree are reflected in the browser. 

- ATTRIBUTE NODES
> The opening tags of HTML elements can carry attributes and these are represented by **attribute nodes** in the DOM tree.

- TEXT NODES
> Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node.

- Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes. 

> STEP 1: ACCESS THE ELEMENTS 

>> SELECT AN INDIVIDUAL ELEMENT NODE 
>>> `get ElementByld () ` `querySelector () `

>> SELECT MULTIPLE ELEMENTS (NODELISTS)
>>> `getElementsByClassName() `  `getElementsByTagName() `
`querySelectorAll()`

>>TRAVERSING BETWEEN ELEMENT NODES
>>> `parentNode` `previousSibl ing / nextSibl ing `
`firstChild / lastChild `

> STEP 2: WORK W ITH THOSE ELEMENTS 

>> ACCESS/ UPDATE TEXT NODES
>>> `nodeValue`

>> WORK WITH HTML CONTENT 
>>> `innerHTML` `textContent` `create Element()` ` createTextNode()`
`appendChild () / removeChild ()`

>> ACCESS OR UPDATE ATTRIBUTE VALUES
>>> `className /id ` `hasAttr i bute()` `getAttribute()``setAttribute()`
`removeAttribute()`

- Caching DOM Queries
> when you need to work with an element more than once , you should use a variable to store the result of this query 
>> `let itemOne= getElementById('one');`

- ACCESSING ELEMENTS 
> `getElementByld('one') `
>`querySelector( 'li.hot') `
>`getElementsByClassName( ' hot ' )`
> `getElementsByTagName( 'li ') `
> `querySelectorAll ( 'li.hot')`

- TRAVERSING THE DOM 
>> `firstChild``lastChild `
>>`previousSibling``nextSibling`
>>`parentNode `

- WHITESPACE NODES 
>> `previousSibling`
`nextSibling`
`firstChild`
`lastChild`

- PREVIOUS & NEXT SIBLING 
>>` var startltem = document.getElementByid('two');`
`var prevltem startltem.previousSibling;`
`var nextltem = startitem.nextSibling;`
`prevltem.className 'complete ' ;`
`nextltem.className 'cool'; `

- FIRST & LAST CHILD 
>> `var startltem = document.getElementsByTagName('ul ') [O] ;`
`var firstltem = startltem. firstChild;`
`var lastltem = startitem.lastCh i ld;`

`firstltem.setAttribute('class ' , 'complete');`
`lastitem.setAttribute('class', ' cool');` 

- ACCESS & UPDATE A TEXT NODE WITH NODE VALUE
>When you select a text node, you can retrieve or amend the content of it
using the node Va 1 ue property. 
>> `document.getElementByid( 1 one 1 ).firstChild.nextSibling. nodeValue;`

# Application Programming Interface (API).
> user interface let humans interact with programs ,APIs let program and **Script** talk to each other .The DOM states what your script can ask the browser about the current page , and how to tell the browser to update what is being shown to the user .