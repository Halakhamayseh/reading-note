# HTML Links, JS Functions, and Intro to CSS Layout

# Links
-**a**  are created using the `<a>` element. Users can click on anything between the opening `<a>` tag and the closing `</a>` tag. You specify which page you want to link to using the href attribute.Writing Links

>>`<a href="http://www.imdb.com">link</a>`


# EmaiL Links
- **mailto** To create a link that starts up the user's email program and addresses an email to a specified email address.

>>`<a href="mailto:jon@example.org">Email Jon</a>`

# opening Links in An  new Window
- targetIf you want a link to open in a new window, you can use the target attribute on the opening` <a>`  tag. The value of this attribute should be _blank
>> `<a href="http://www.imdb.com" target="_blank">Int</a>`

# Linking to A specific PArt of the same page

- you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top

>> `<a href="#arc_shot"> Shot</a>`

# Linking to A specific Part of Another Page
- If you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique

>> `<a href="http:/www.htmlandcssbookcom/#bottom">`


# LAYOUT 

1. Normal Flow
>> position:static

2. Relative Positioning
>> position:relative

3. Absolute Positioning
>> position:absolute

4. Fixed Positioning
>>  position:fixed

5. Overlapping Elements
>> z-index

6. Floating Elements
>> float 


# Screen Sizes

- Different visitors to your site will have different sized screens that show
different amounts of information, so your design needs to be able to
work on a range of different sized screens

# Screen Resolution
- Resolution refers to the number of dots a screen shows per inch. Some
devices have a higher resolution than desktop computers and most
operating systems allow users to adjust the resolution of their screens

# Page Sizes
 Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around 960-1000 pixels wide
(since most users will be able to see designs this wide on their screens).

# Fixed Width Layouts
- Fixed width layout
designs do not
change size as the
user increases
or decreases
the size of their
browser window.
Measurements tend
to be given in pixels.


# Liquid Layouts
- Liquid layout designs
stretch and contract
as the user increases
or decreases the
size of their browser
window. They tend to
use percentages



# Example Grid
- Possible Layouts:
960 Pixel wide
12 Column Grid

# Multiple Style Sheets
>> `@import`
-  Your HTML page can link
to one style sheet and that
stylesheet can use the @import
rule to import other style sheets

>> `link`
- On this page you can see the
other technique for including
multiple style sheets. Inside the
`<head>` element is a separate
`<link>` element for each style
sheet