# Domain Modeling
> Domain modeling is the process of creating a conceptual model in code for a specific problem. 

# TABLE
- What is a table?
>A table represents information in a grid format.

- Basic Table Structure?
> The `<table>` element is used to create a table. The contents of the table are written out row by row. 
> `<tr>` You indicate the start of each row using the opening `<tr>` tag. (The tr stands for table row.)It is followed by one or more.
-` <td>` elements (one for each cell in that row). At the end of the row you use a closing `</tr>` tag.
> `<td>` Each cell of a table is represented using a `<td>`
element. (The td stands for table data.)At the end of each cell you use a
closing `</td>` tag.

- Table Headings 
> The `<th>` element is used just like the `<td>` element but its purpose is to represent the
heading for either a column ora row. (The th stands for table heading.) 

- Spanning Columns
> The colspan attribute can be used on a `<th>` or `<td>` element and indicates how many columns that cell should run across.


- Spanning Rows
> The rowspan attribute can be used on a `<th>` or `<td>` element to indicate how many rows a cell should span down the table.


- Long Tables
> There are three elements that help distinguish between the main content of the table and
the first and last rows (which can contain different content).
These elements help people who use screen readers and also
allow you to style these sections in a different manner than the rest of the table (as you will see
when you learn about CSS). `<thead>` The headings of the table should sit inside the `<thead> ` element.
`<tbody>` The body should sit inside the `<tbody>` element.
`<tfoot>`The footer belongs inside the`<tfoot>` element.


- Old Code: Border & Background
> The border attribute was used on both the ` <table> `and `<td>` elements to indicate the width of the border in pixels
>> ` bgcolor="#cccccc"`


# Creating an Object
- create an object
>`let hotel =new object();`
>`hotel.rooms=40;`
>`hotel.booked=25;`
- add properties to an object 
> `car.hotel='quay';`
- add method to an object
> `hotel.checkAvailability =function(){return this.rooms-this.booked;};`
- updating an object 
>`hotel.name='paris;'`OR `hotel['name']='paris';`
-delete a property
>`delete hotel.name;`
- clear value
>`hotel.name='';`

- CREATING MANY OBJECTS
 > `function Hotel (name, rooms, booked)`
 >`{this . name = name ; th is. rooms = rooms;this booked = booked; `
 >` this. checkAvailability = function()`
 >`return this.rooms - this. booked; `
 >`};`
 > `}`

- Accessing An object and don't notation
>`let hotelName=hotel.name;`

-  WAYS TO CREATE OBJECTS
- CREATE THE OBJECT, THEN ADD PROPERTIES & METHODS 
- LITERAL NOTATION
`var hotel = {}`
`hotel .name= 'Quay';`
`hotel .rooms = 40;`
`hotel.booked = 25;`
`hotel.checkAvailabil ity =function()`
`return this.rooms - this .booked;`
`} ; `

- OBJECT CONSTRUCTOR NOTATION
`var hotel = new Object();`
`hotel.name = 'Quay';`
`hotel .rooms = 40;`
`hotel . booked= 25;`
`hotel.checkAvailability =function()`
`return this .rooms - this.booked;`
`} ; `

- A FUNCTION IN GLOBAL SCOPE
> `function windowSize() {`
`var width= this . innerWidth;`
`var height = this .innerHeight;`
`return [height,width];`

- Global Variables
> and this.width refers to the width variable:
`var width = 600 ;` 
`var shape = {width: 300};`
`var showWidth-= function()`
`document .write(this.width) ) ;`
`};`
`showWidth(); ` 

- Arrays are objects 
- an object
>`costs={room1:30,room2,34,room3:44};`

- an array
>`costs =[30,34,44];`


- WHAT ARE BUILT-IN OBJECTS?
>Browsers come with a set of built-in objects that represent things like the
browser window and the current web page shown in that window.

- GLOBAL OBJECTS: DATE OBJECT (AND TIME) 
> `getDate() setDate() `
> `getDay ()`
> `getFul 1 Year() setFul 1 Year ()`
>`getHours () setHours ()`
> `getMinutes () setMinutes ()`
>`getMonth () setMonth ()`
>`getSeconds() setSeconds()`
>`get Ti me() setTi me()`