# FORMS

- Why Forms?
> The best known form on the web

- Form Controls
> several types of form controls
>> - ADDING TEXT:
>>> Text input (single-line) ,Password input,Text area (multi-line)
>> - Making Choices
>>> Radio buttons,Checkboxes,Drop-down boxes
>> - Submitting Forms:
>>> - Submit buttons, Image buttons
>> - Uploading Files:
>>> File upload

- Form Structure
> `<form>`This element should always carry the action attribute and will usually have a method and id attribute too.
> `action` Every `<form>` element requires an action attribute. Its value is the URL for the page on the server that will receive the
information in the form when it is submitted.
>` method` Forms can be sent using one of two methods: get or post
>> The **get** method, the values from the form are added to the end of the URL specified in
the action attribute.
>>The **post** method the values are sent in what are known as HTTP headers.
>> The **id** value is used to identify the form distinctly from other elements on the page

## INPUTS
- Text Input`type="text"`
- Password Input`type="password"`
- Text Are`<textarea>`
- Radio Button`type="radio" checked="checked"`
- Checkbox `type="checkbox"`
- File Input Box `type="file"`
- Submit Button `type="submit"`
- Image Button `type="image"`
- Button & hidden Controls `<button>` `<input> type="hidden"` 
-  Email & URL Input `type="email"`, `type="url"`


# Dropdown 
- Drop Down List Box `<select>``<option>`
- Multiple Select Box `<select>``multiple`





# Label 
- Labelling Form Controls`<label>`

# Grouping Form Elements
- `<fieldset>` `<legend>`
# Form Validation
- `required="required"`

#  Date Input
- `<input>``type="date"`


#  Search Input
- `type="search"`


## CSS allows you to create rules that control the way that each individual box

- CSS Associates Style rules with HTML elements.
- CSS Properties Affect How Elements Are Displayed.

> `p {font-family: Arial;}` p : selector , font-family: declaration , arial: value

- Using External CSS
> `<link>``href`

- Using Internal CSS
> `<style>`

### CSS Selectors
- Universal Selector `*`
- Type Selector `h1, h2, h3 {}`
- Class Selector  `.note {}`
- ID Selector  `#introduction {}`
- Child Selector  `li>a {}`
- Descendant Selector `p a {}`
- Adjacent Sibling Selector `h1+p {}`
- General Sibling Selector `h1~p {}`

# EVENT 
> the events that occur in the browser while you are browsing the web

- HOW EVENTS TRIGGER JAVASCRIPT CODE
1. **SELECT ELEMENT**Select the element node(s) you want the script to respond to.
2. **SPEC! FY EVENT**Indicate which event on the selected node(s) will trigger the response. 
3. **CALL CODE**State the code you want to run when the event occurs. 

## TRADITIONAL DOM EVENT HANDLERS 
> `element .onevent functionName ;` 
> ELEMENT EVENT CODE 

- EVENT LISTENERS 
> `element .addEventlistener('event', functionName [, Boolean]) ;`