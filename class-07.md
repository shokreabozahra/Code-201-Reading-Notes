# Domain Modeling
## is a conceptual model of the domain that incorporates both behavior and data. In ontology engineering, a domain model is a formal representation of a knowledge domain with concepts, roles, datatypes, individuals, and rules, typically grounded in a description logic.
# Usage
## A domain model is generally implemented as an object model within a layer that uses a lower-level layer for persistence and "publishes" an API to a higher-level layer to gain access to the data and behavior of the model. In the Unified Modeling Language (UML), a class diagram is used to represent the domain model.

# Chapter 6: Tables
## How to create tables
- The (table) tag defines an HTML table.

- Each table row is defined with a (tr) tag. Each table header is defined with a (th) tag. Each table data/cell is defined) with a (td) tag.

- By default, the text in (th) elements are bold and centered.

- By default, the text in (td) elements are regular and left-aligned.

### Long Tables:
#### should have 3 elements
- (thead)
The headings of the table should
sit inside the (thead) element.
- (tbody)
The body should sit inside the
(tbody) element.
- (tfoot)
The footer belongs inside the
(tfoot) element


> Inside each row there are a number of cells
represented by the (td) element (or (th) if it is a
header).

> You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.

> For long tables you can split the table into a (thead),
(tbody), and (tfoot).
<hr>


# Chapter 3: Functions, Methods, and Objects
## CREATING MANY OBJECTS:CONSTRUCTOR NOTATION 
### Sometimes you will want several objects to represent similar things.
### Object constructors can use a function as a template for creating objects.
### First, create the template with the object's properties and methods. 

## GLOBAL OBJECTS:STRING OBJECT
### Whenever you have a value that is a string, you can use the properties and methods of the String object on that value.

- In an object, variables are known as properties of the
object; functions are known as methods of the object.
- Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.

>JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.

>Arrays and objects can be used to create complex data
sets (and both can contain the other). 




