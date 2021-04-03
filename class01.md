# Read: 01 - Introductory HTML and JavaScript

## how the web works: i understand how it works When you visit a website, the web server hosting that site could be anywhere in the world.
 
## HTML:
* what: HTML is HyperText Markup Language , it is responsible to create the structure of the webpage

* why:because without the html the browser canot understand the content and the sturctuer of the page(text,image ,audio,video,paragraph)

* how: html contain some element to write it is openning tag, closing tag, content and attributes.

### the structuer of html:
~~~~
<!DOCTYPE html>
<html>
<head>
 <title>This is the Title of the Page</title>
</head>
<body>
</body>
</html>
~~~~

### examples:
* open tag : `<p>`
* close tag:  `</p>` 
* attribute:  `<p  class="yazan"></p>`
* content:  `<h1>my name is yazan</h1>` 

some tags in html:
 * `<!-- content -->`:comment
* `<h1>` to `<h6>` : header 
* `<p>`: paragraph
* `<a>`: add hyperlink
* `<img>`: add image
* `<ul>`: add unorderd list
* `<ol>`: add orderd list

### defention list :
* Web browser:A web browser is application software for accessing the World Wide Web

* Web server:A web server is server software, or a system of one or more computers dedicated to running this software, that can satisfy client HTTP requests on the public World Wide Web or also on private LANs and WANs.

* Screen reader:A screen reader is a form of assistive technology that renders text and image content as speech or braille output

* Internet service provider:An Internet service provider is an organization that provides a myriad of services for accessing, using, or participating in the Internet

 * Domain Name System(DNS): is a hierarchical and decentralized naming system for computers, services, or other resources connected to the Internet or a private network

* CSS: Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a markup language such as HTML

* tag : HTML tags are like keywords which defines that how web browser will format and display the content

* `<!DOCTYPE>`: Defines the version of html we are going to use

* id: the id attribute specifies a unique id for an HTML element (the value must be unique within the HTML document).

* The id attribute is most used to point to a style in a style sheet, and by JavaScript (via the HTML DOM) to manipulate the element with the specific id.

* class : we give class for many tags to give them all attributes togther

* Block Elements:Some elements will always appear to start on a new line in the browser window. These are known as block level elements. Examples of block elements are 
`<h1>`, `<p>`, `<ul>`, and `<li>` 

* Inline Elements:Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.Examples of inline elements are `<a>`, `<b>`, `<em>`, and `<img>`.

* `<div>`: element allows you to group a set of elements together 
in one block-level box.

* `<span>`:The `<span>` element acts like an inline equivalent of the `<div>`element.

* `<iframe>`:An iframe is like a little window that has been cut into your 
page — and in that window you can see another page

* `<meta>`: discription about the webpage such the contet or author of the website and its useful for search engine


#### semantic tags:
 * `<header>` 
 * `<footer>`
* `<nav>`
*  `<article>`
* `<aside>`
* `<section>` 
* `<figcaption>`
* `<figure>`

### tips for building your website:
#### whenever a developer wants to build his own website, he must know who are the users who will use the site, and must know what services will be provided and what features will be present on the site and what are the preferences that will be present on the site over all other sites What is the motivation that will make users enter the site and what services do users want, and the site must be easy to use and navigate smoothly. There are some steps that may include a good design for the site such as creating a ware frame before the main design is also very important in the site to be Color-coordinated In order to be suitable for viewing, the site must be divided in an orderly way so that the user can see the content HTML in good way



#### javascript:
* what: it is programming language allows you to make web pages more interactive  and make the website more user friendly
 
* why: because javascript accessing , modifying  the content and it is react to events

* how: we can write javascript inside the html through script tag `<script>` or we can make external  file 

#### in order to use javascript we need to know the basic programming concepts and the syntax of the language and how it use in the website some event that work in javascript( slideshow,forms,reload the page ,filter the data,......)

#### defention in javascript :
* script:means a series of instructions that a computer can follow it step by step to achieve a goal in.

* flowchart: it is hight-level view of the tasks can be represented 
 
* object:is a standalone entity, with properties and type

* method:are actions that can be performed on objects

* Properties:characteristic found within the object

* Events : is an action that occurs as a result of the user interaction


#### some syntax in javascript:
* `document.wirte(content);`
* `console.log(content);`
* `alert();`
* `function name(parameter){return value;}`
* `var` ;
* `//` and `/* */` for the comment