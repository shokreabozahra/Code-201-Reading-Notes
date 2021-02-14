# WHAT IS AN OBJECT?
## object can be a variable, a data structure, a function, or a method, and as such, is a value in memory referenced by an identifier. In the object-oriented programming paradigm object can be a combination of variables, functions.

### Each Object has one or more properties. Each property consists of a property-key and it’s associated value.
### var object1 = { 
###          name: "First"
###             }
### So object1 has 1 property a name property with property-key name and it’s associated string VALUE “FIRST”
## CREATING· OBJECTS USING LITERAL NOTATION 
### To create an Object, you can use the literal notation, you directly create an Instance of the object, with the properties being separated by a comma-,

#### var myObj = {
####       type: 'fancy',
####       disposition: 'sunny' 
#### };
<hr>

# Chapter 5: “Document Object Model”

### Document Object Model (DOM) is defined by W3C as a set of recommendations. The DOM core recommendations define a set of objects, each of which represents some information relevant to the XML document. There are also well defined relationships between these objects, to represent the document's organization.

### A DOM parser essentially reads the XML document and constructs a tree structure in memory that represents the original document,  This tree is composed of well-defined objects. Applications can then navigate through the branches of this tree and manipulate the XML. The parser implementations, including the reference implementation, internally use a SAX parser to read the XML into memory. The XML is then analyzed for the relationships between the component parts and is organized into a tree structure that can be traversed.

<img src="https://ars.els-cdn.com/content/image/3-s2.0-B9781558609006500130-f09-02-9781558609006.jpg?_">


## SELECTING AN ELEMENT FROM A NODELIST
### There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want. 
- THE item() METHOD
- Array syntax

Property / Method	     |  Description
-----------------        |   -----------
attr.isId	             |  Returns true if the attribute is of type Id, otherwise it returns false
attr.name	             |  Returns the name of an attribute
attr.value            	 |  Sets or returns the value of the attribute
attr.specified	         |  Returns true if the attribute has been specified, otherwise it returns false 
nodemap.getNamedItem()	 |  Returns a specified attribute node from a NamedNodeMap
nodemap.item()	Returns  |  the attribute node at a specified index in a NamedNodeMap
nodemap.length	Returns  |  the number of attribute nodes in a NamedNodeMap
nodemap.removeNamedItem()|	Removes a specified attribute node
nodemap.setNamedItem()	 |  Sets the specified attribute node (by name)

<hr>


>Whenever a DOM query can return more than one
node, it will always return a Nadel i st.

>From an element node, you can access and update its

>content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques. 
In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).

>Browsers offer tools for viewing the DOM tree