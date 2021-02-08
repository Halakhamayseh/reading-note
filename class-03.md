# HTML Lists, Control Flow with JS, and the CSS Box Model

##  HTML provides us with three different types

- Ordered lists
>>are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.

-Unordered lists 
>> are lists that begin with a bullet point (rather than characters that indicate order)

-Definition lists
>> are made up of a set of terms along with the definitions for each of those terms

- Nested Lists
>> You can put a second list inside an <li> element to create a sub-list or nested list.


1. Ordered Lists

- ```<ol>``` The ordered list is created with the``` <ol>``` element.```<li>``` Each item in the list is placed between an opening ``` <li>``` tag and a closing ```</li>``` tag. (The li stands for list item.)


2. Un Ordered Lists

- ```<ul>```The unordered list is created with the ```<ul>``` element.```<li>```Each item in the list is placed between an opening ```<li>``` tag and a closing ```</li>``` tag. (The li stands for list item.


3. definitiOn Lists

- ```<dl>``` The definition list is created with the ```<dl>``` element and usually consists of a series of terms and their definitions.Inside the ```<dl>``` element you will usually see pairs of ```<dt> ```and ```<dd>``` elements.```<dt>```This is used to contain the term being defined (the definition term).```<dd>``` This is used to contain the definition

4. Nested Lists

- You can put a second list inside an <li> element to create a sub-list or nested list.

# BOXES 

>> Box dimensions 
1. width
-  ```.box {width: 300px;}```
2. height
- ``` p {height: 75%;}```

>> Limiting Width
1. min-width
- ```min-width: 450px;```

2. max-width 
- ```max-width: 650px;```

>> Limiting Height
 1. min-height 
 - ``` min-height: 10px;```

 2. max-height
 - ```max-height: 30px;```

 >> Overflowing Content

 1. hidden
- This property simply hides any extra content that does not fit in the box
2. scroll
- This property adds a scrollbar to the box so that users can scroll to see the missing content

# Border, Margin & Padding

> Every box has three available properties that can be adjusted to control its appearance:

1. Border 
- Every box has a border (even if it is not visible or is specified to
be 0 pixels wide). The border separates the edge of one box from another

2. Margin 
- Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.


3. Padding
- Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents

> Border Width
 >> ```border-width: 2px;```

 > Border Style
>> ```border-style: solid;```

> Border Color
>> ```border-color: #0088dd;```

>>> Shorthand border
+ ``` border: 3px dotted #0088dd;```

#  Inline/Block
> display 
 - ```display: inline;```

 > Hiding Boxes (visibility)
 1. hidden
 - This hides the element.
2. visible
- This shows the element

# border-image
- ``` -moz-border-image: url("") 11 11 11 11 stretch;```
- ```webkit-border-image: url("")11 11 11 11 stretch;```
- ```border-image: url("")11 11 11 11 stretch;```

# Box Shadows

1. Horizontal offset
- Negative values position the shadow to the left of the box.

2. Vertical offset
Negative values position the shadow to the top of the box.

3. Blur distance
- If omitted, the shadow is a solid line like a border.

4. Spread of shadow
- If used, a positive value will cause the shadow to expand in all directions, and a negative value will make it contract.

# Rounded Corners

1. border-radius
- ```border-radius: 10px;```
- ```border-top-right-radius```
- ```border-bottom-right-radius```
- ```border-bottom-left-radius```
- ```border-top-left-radius```
>> ```border-radius: 1em 4em 1em 4em / 2em 1em 2em 1em;```


# ARRAYS 
>> An array is a special type of variable. It doesn't just store one value. it stores a list of values.

# IF ELSE STATEMENTS 

# Switch Statements 

# LOOP 
# WHILE 
# DO WHILE
