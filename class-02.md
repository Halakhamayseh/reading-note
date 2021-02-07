# HTML , CSS & JS

### When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page


***we focus on how to add markup to the text that appears on your pages***

- **Structural markup**
>> the elements that you can use to describe both headings and paragraphs

- **Semantic markup**
>>  that something you have written is a quotation


# HEADING
- HTML has six **levels** of headings

```
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>

```


# Paragraphs
-  surround the words that make up the paragraph with an opening ``` <p>``` tag and closingv``` </p>``` tag.

# Bold & iTalic
- ```<b>``` By enclosing words in the tags``` <b>``` and``` </b>``` we can make characters appear bold.

- ``` <i> ``` By enclosing words in the tags ```<i>``` and ```</i>```we can make characters appear italic.

# superscript & subscript
- the ```<sup>``` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 9

the <sub> element is used to contain characters that should be subscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 10

# line Breaks & Horizontal

-if you want to add line break in the middel of paragraph just use this tag ```<br>``` 
- You can add a horizontal rule between sections using the```<hr>```tag

# semantic markdown
- Strong 
>> The use of the ```<strong>``` element indicates that its content has strong importance.

- Emphasis 
>>The ```<em>``` element indicates emphasis that subtly changes the meaning of a sentence.

- blockquote
>> The ```<blockquote>``` element is used for longer quotes that take up an entire paragraph. Note how the ```<p>``` element is still used inside the ```<blockquote>```element.

- quotes
>>The ```<q>``` element is used for shorter quotes that sit within a paragraph

# abbreviations & acronyms
- if you use ana bbreviation or an acronym, then the ```<abbr>```element can be used .

# changes To content
 
 - ```<ins> </ins>```  ```<del> </del> ```  The ```<ins>``` element can be used to show content that has been inserted into a document, while the ```<del>``` element can show text that has been deleted from it

- ```<s> </s>```The element indicates something that is no longer accurate or relevant (but that should not be deleted).

# CSS 
## INTRO TO CSS
### CSS allows you to create rules that specify how the content an element should appear 

- A CSS rule contains two parts: a selector and a declaration.
>> ```p{font-size:20px;} ```
**p : selector**
**font-size:20px; :declaration**

- CSS **declarations** sit inside curly brackets and each is made up of two
parts: a property and a value

>> font-size : property
>> 20px : value

# using internal css 
- ```<style>``` You can also include CSS rules
within an HTML page by placing
them inside a ```<style>``` element,
which usually sits inside the
``` <head>``` element of the page

# selectors
1. universal selector ```*{}```
2. type selector ```h1 , h2{}```
3. class selector ``` .doc {}```
4. id selector ```#doc{}```
5. child selector ``` li>a{}```
6. descendant selector ```p a {}```
7. Adjacent Sibling Selector ```h1+p {} ```
8. Adjacent Sibling Selector  ``` h1~p{}```


# Basic JS instructions
- A script is a series of instructions that a computer can follow one-by-one. 

>> statements 
>> comments 

## variable ?
- container that hold value
- to define variable 
>> ```var username; ```
>> ``` var quan=9;```

## data type 
+ Number
+ string 
+ Boolean


# Array 
- An array is a special type of variable ,it stors a list of values.
>>``` var colors ;```
>>``` colors=['red','green','blue']; ```
>OR
>> ```var colors =new array('red','green','blue');```

# operators
- arithmetic 
1. ```+```
2. ```-```
3. ```/```
4. ```*```
5. ```++```
6. ```--```
7. ```%```
 
 - logic
 1. ```>```
 2. ```<```
 3. ```&&```
 4. ```||```

 - string
>> ```var firstName = 'Ivy ' ;```
```var lastName = ' Stone' ;```
```var ful l Name = f irstName + l astName ;```

