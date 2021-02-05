# HTML Hypertext Markup Language 
## HTML Describes The Structure of Pages
_describe the structure of a web page, we add code to the words we want to appear on the page_

* Example 
<html>  
<body>
      <h1>This is the Main Heading</h1> 
           <p>This text might be an introduction to the rest of  the page. And if the page is a long one it might  be split up into several sub-headings.<p>
                 <h2>This is a Sub-Heading</h2> 
                      <p>Many long articles have sub-headings so to help  you follow the structure of what is being written.  There may even be sub-sub-headings (or lower-level  headings).</p>
                            <h2>Another Sub-Heading</h2>
                                  <p>Here you can see another sub-heading.</p>
                                    </body>
                                    </html>

> They tell you something about the information that lies between their opening and closing tags.des Cription 


>> The opening <html> tag indicates that anything between it and a closing </html> tag is HTML code. 

>> The <body> tag indicates that anything between it and the closing </body> tag should be shown inside the main browser window.
>> Words between <h1> and </h1> are a main heading.
>> A paragraph of text appears between these <p> and </p> tags.
>> Words between <h2> and </h2> form a sub-heading.
>> Here is another paragraph between opening <p> and closing </p> tags. 
>> Another sub-heading inside <h2> and </h2> tags.
>> Another paragraph inside <p> and </p> tags.The closing </body> tag indicates the end of what should appear in the main browser window.
>> The closing </html> tag indicates that it is the end of the HTML code.

# Attributes teLL uS more about eLementS
 >> They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.
 >> Opening tags can carry attributes.
>> Attributes require a name and a value
>> you need to know what tags are available for you to use, what they do, and where they can go.

 * Example

 > <p lang="en-us">Paragraph in English</p>
 
 - Tags usually come in pairs
 
 **WHAT**will You See?_

 >you will see everything wrote in html code between head tags ,body tags and footer tags.

 **WHY**_We Use Html?_
 >> to build the structure for web page.

 **HOW**_We Use Html?_
>> must to learn the html , how and wherem wirte the code and using tags ,what tools you must use, learn more about web pages structure .


# Extra Mrakup
## Markup Syntax
> Markup uses simple Markdown-like character delimiter syntax with custom 
extensions. There are four types of elements:

- **Single line** elements format a line of text such as creating a heading.
+  ## Second Level Heading

- **Multiline** elements format multiple lines of text such as creating lists or callouts.

- **Span** elements format a span of characters such as adding emphasis.
/// This markup renders as one *line*
//: Span elements *nest **inside other** span* elements


- **Link** elements add text based links such as a mailto, or inline assets such as images.
+ [Swift](http://swift.org)
+ ![Swiftie the cat](cat.png)


# HTML5 Layout
## A web page being rendered in the browser consists of many things - logo, informative text, pictures, hyperlinks, navigational structure and more.

> Semantic Markup
>>Semantic markup expresses its meaning and purpose clearly to the developers and to the browser .  **<div class="header">...</div>**


>>As you can see, these elements are quite expressive and you can immediately get an idea of the intended purpose. The following figure shows a sample page layout designed using these elements

+ <header>
+ <footer>
+ <section>
+ <article>
+ <aside>
+ <nav>

# Header Element
 > The <header> element represents the header of the whole page or a section of it.

- <header><h1>This is page heading</h1></header>

# Nav Element
>The <nav> element is intended to house navigation menus or any kind of navigational structure such as hyperlinks.

- <nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">About Us</a></li>
<li><a href="#">Contact Us</a></li>
</ul>
</nav>

# Section Element
 > the <section> element represents a generic section of a document or application. The <section> element should not be confused with the <div> element. The <section> element is a thematic grouping of content whereas the <div> doesn't have any such restriction. 

- <section>
  <h1>This is a section heading</h1>
  <p>
    Hello world! Hello world! Hello world!
    Hello world! Hello world! Hello world!
    Hello world! Hello world! Hello world!
  </p>
</section>



# Article Element
>It is expected that the content in the article element should be independently distributable or reusable as in the case of content syndication

-<article>
  <h1>This is article heading</h1>
  <p>
    Hello world! Hello world! Hello world!
    Hello world! Hello world! Hello world!
    Hello world! Hello world! Hello world!
  </p>
</article>


# Asid Element
>The <aside> element is intended to house content that is related to the surrounding content but at the same time is a standalone piece of content in itself. 

-<aside>
  <figure>
    <img src="images/laptop.png" height="100px" width="100px" />
    <figcaption>Figure caption goes here</figcaption>
  </figure>
  <p>
    Hello world! Hello world! Hello world!
    Hello world! Hello world! Hello world!
  </p>
</aside>


# Footer Element
> The <footer> element represents the footer of the whole page or a <section> element

-<footer>
  <hr>
  Copyright (C) 2013. All rights reserved.
</footer>



# PROCESS & DESIGN
- How to approach building a site
- Understanding your audience and their needs
- How to present information visitors want to see


### It looks at who might be visiting your site and how to ensure the pages feature the information those visitors need. It also covers some key aspects of design theory to help you create professional looking sites. In this chapter, we will look at:

+ How to understand the audience your site may attract and what information they will expect to find on it
+ How to organize information so that visitors can find what they are looking for
+ Design theory for presenting information in a way that helps visitors achieve their goals
+ Design tips to help you create more attractive and professional sites

## WHO IS THE SITE FOR?
> Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.

> It can be helpful to ask some questions about the people you would expect to be interested in the subject of your site.

> If you ask a client who a site is for, it is not uncommon for them to answer “the entire world.”

# JavaScript
***ABC***

# A
> What is a script and how do i create one?
>>A script is a series of instructions that a
computer can follow to achieve a goal.
>>Each time the script runs, it might only use a subset of
all the instructions. 
>>To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help). 
>>Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically. 

## DEFINING A GOAL & DESIGNING THE SCRIPT 
> Consider how you might approach a different type of script
1. The script is triggered when the button is clicked.
2. It collects the name entered into the form field.
3. It checks that the user has entered a value.
4. If the user has not entered anything, a message
will appear telling them to enter a name.
5. If a name has been entered, calculate the cost of
the sign by multiplying the number of letters by
the cost per letter.
6. Show how much the plaque costs

# B
> How do computers fit in with the world arounf them?
>>COMPUTERS CREATE MODELS OF THE WORLD USING DATA

# OBJECTS & PROPERTIES

## object 
> In computer programming, each physical thing in
the world can be represented as an object.
>Each object can have its own:
* Properties

* Events
>There are common ways in which people interact with each type of object.
> what does an event do? 
>>Programmers choose which events they respond to,When a specific event happens, that event can be used to trigger a specific section of the code. 

* Methods
>Methods typically represent how people (or other
things) interact with an object in the real world.
>WHAT DOES A METHOD DO?  
>>The code for a method can contain lots of
instructions that together represent one task.
>>When you use a method, you do not always need to
know how it achieves its task; you just need to know
how to ask the question and how to interpret any
answers it gives you.

## PROPERTIES (CHARACTERISTICS)
>Programmers call these characteristics the properties of an object
>Each property has a name and a value, and each of these name/value pairs tells you something about each individual instance of the object


## HOW A BROWSER SEES A WEB PAGE ?
1. RECEIVE A PAGE AS HTML CODE Each page on a website can be seen as a separate document .So, the web consists of many sites, each made up of one or more documents.
2. CREATE A MODEL OFTHE PAGE AND STORE IT IN MEMORY The model shown on the right hand page is a representation of one very basic page. Its structure is reminiscent of a family tree. At the top of the model is a document object,which represents the whole document.  
3. USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN If there is no CSS, the rendering engine will apply default styles to HTML elements. However,
the HTML code for this example links to a CSS style sheet, so the browser requests that file and displays the page accordingly.

# C
## HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER ?
## How do i wirte a script fo a web page?
> JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script.
>LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE
>>You may see JavaScript in the HTML between
opening <script> and closing </script> tags
(but it is better to put scripts in their own files). 
