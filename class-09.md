# Chapter 7: “Forms” 
## How Forms Work
### Web form or HTML form on a web page allows a user to enter data that is sent to a server for processing. Forms can resemble paper or database forms because web users fill out the forms using checkboxes, radio buttons, or text fields.
<img src="https://simfatic.com/forms/help/v40/form-working.jpg">

## Form Structure
### The HTML (input) element is the most used form element.
### An (input) element can be displayed in many ways, depending on the type attribute.
## Text Area
### The textarea element is used to create a mutli-line text input. Unlike other input elements this is not an empty element. It should therefore have an opening and a closing tag. Any text that appears between the opening textarea and closing /textarea tags will appear in the text box when the page loads.

>Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.

>HTML5 introduces new form elements which make it
easier for visitors to fill in forms.
<hr>

# Chapter 14: “Lists, Tables & Forms”
## Images for Bullets
### You can specify an image to act as a bullet point using the list-style-image property. The value starts with the letters url and is followed by a pair of parentheses. Inside the parentheses, the path to the image is given inside double quotes. This property can be used on rules that apply to the (ul) and (li) elements.
## Styling Fieldsets & Legends
### Fieldsets are particularly helpful in determining the edges of a form. In a long form they can help group together related information within it. The legend is used to indicate what information is required in the fieldset. Properties commonly used with these two elements include: width is used to control the width of the fieldset. In this example, the width of the fieldset forces the form elements to wrap onto a new line in the correct place. (If it were wider, the items might sit on one line.)
## Cursor Styles
- auto
- crosshair
- default
- pointer
- move
- text
- wait
- help
- url("cursor.gif");
>Forms are easier to use if the form controls are
vertically aligned using CSS.

>Forms benefit from styles that make them feel more
interactive.
<hr>

# Chapter 6: “Events”
## Event types
<img src ="https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types-1200x675.jpg">

## THREE WAYS TO BIND AN EVENT TO AN ELEMENT
- HTML EVENT HANDLERS
- TRADITIONAL DOM EVENT HANDLERS
- DOM LEVEL 2 EVENT LISTENERS 
## Event Flow :
### Event flow is the order in which event is received on the web page. If you click on an element like on div or on the button , which is nested to other elements, before the click is performed on the target element.
>When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user. 

>You can use event delegation to monitor for events
that happen on all of the children of an element. 

>The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.

