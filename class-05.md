# IMAGE , COLOR , TEXT

1. IMAGES 
>> Choosing Images for Your Site
>> Storing Images on Your Site

- To add an image into the page you need to use an `<img>`
element. 

- `src` This tells the browser where it can find the image file.

- `alt` This provides a text description of the image which describes the image if you cannot see it.

- `<img src="images/quokka.jpg" alt="A family of quokka"  />`

>> Height & Width of Images
- `height`
This specifies the height of the image in pixels.
- `width`
This specifies the width of the image in pixels.

- `<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" />`

>> Aligning Images Horizontally
- `align `The align attribute was commonly used to indicate how the other parts of a page should flow around an image.

>>  Aligning Images Vertically

- There are three values that the align attribute can take that control how the image should align vertically with the text that surrounds it:

- `top` `<img src="images/bird.gif"  align="top" />`This aligns the first line of the surrounding text with the top of the image.

- `middle` `<img src="images/bird.gif"  align="middle"/>`T This aligns the first line of the surrounding text with the  middle of the image.

- `bottom` `<img src="images/bird.gif"  align="bottom"/>` This aligns the first line of the surrounding text with the bottom of the image.

>> Tools to Edit & Save Images

>>> Use GIF or PNG format when saving images with few colors or large
areas of the same color. 

- Image Formats: JPEG
- Image Formats: GIF

>> Figure and Figure Caption

- `<figure>` Images often come with captions. HTML5 has introduced a new `<figure>` element to contain images and their caption so that the two are associated.

- `<figcaption>` The `<figcaption>` element has been added to HTML5 in order to allow web page authors to add a caption to an image


2. Foreground Color

- **rgb values** These express colors in terms of how much red, green and
blue are used to make it up. For example: rgb(100,100,90)

- **hex codes** These are six-digit codes that represent the amount of red,green and blue in a color, preceded by a pound or hash #sign. For example: #ee3e80

- **color names** There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

- Background Color
>> the background-color property sets the color of the background
for that box.

 - Contrast
 >> When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible

 - **Opacity**  to specify the opacity of an element and any of its child elements
 >> 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).


3. TEXT 

- **Serif** Serif fonts have extra details on the ends of the main strokes of the letters. These details are known as serifs.

- **Sans-Serif** Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.

- **Monospace**
Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts have different widths.)

>> Weight 
-  The font weight not only adds emphasis but can also affect the amount of white space and contrast on a page.

>> Style
- Italic fonts have a cursive aspect to some of the lettering. Oblique
font styles take the normal style and put it on an angle.

>> Stretch
- versions of the font, letters are thinner and closer together

>> Typeface 
- *Serif* fonts have extra details on the end of the main strokes of the letters.

- *Sans-Serif*  Sans-serif fonts have straight ends to letters and therefore have a much cleaner design.

- *Monospace* Every letter in a monospace typeface is the same width.

- *Cursive* Cursive fonts either have joining strokes or other cursive
characteristics, such as handwriting styles.
 
- *Fantasy* Fantasy fonts are usually decorative fonts and are often
used for titles


>> Specifying Typefaces

- font-family `font-family: Georgia, Times, serif;`

>> Size of Type

- font-size `font-size: 12px;`

>> Bold
- font-weight `font-weight: bold;`

>> Article 
- font-style `font-style: italic;`

>> UpperCase & LowerCase
- text-transform 
- `text-transform: uppercase;` `text-transform: lowercase;` `text-transform: capitalize;`

>>Underline & Strike
- text-decoration `none`, `overline` , `blink`, `underline`,`line-through`

- Leading **line-height** `line-height: 1.4em;`

>> Letter & Word Spacing
- **letter-spacing , word-spacing**
- `letter-spacing: 0.2em;`
- `word-spacing: 1em;`

>> Alignment

- text-align 
- **left**
- **right**
- **center**
- **justify**

>> Vertical Alignment
>>> vertical-align
- baseline
- sub
- super
- top
- text-top
- middle
- bottom
- text-bottom


>> Indenting Text
- **text-indent**
- property allows you to indent the first line of text within an element
- `text-indent: -9999px;`

>> Drop Shadow
- **text-shadow**
-  property has become commonly used despite lacking support in all browsers
- `text-shadow: 1px 1px 0px #000000;`

>> First Letter or Line
- You can specify different values for the first letter or first line of
text inside an element
- **:first-letter, :first-line**

>> Styling Links
- **:link, :visited**

- `a:link {color: deeppink; text-decoration: none;}`

- `a:visited {color: black;}`

>> Responding to Users
- **:hover, :active, :focus**

- ` .submit:hover {background-color: #665544;}`
- `.submit:active {background-color: chocolate;}`
- `input.text:focus {color: #665544;}`
