# Read: 06 - JS Object Literals; The DOM



## i understand the concept of the objects it is set of variables and function together to create model of something , the variable will be inside the objects properties ,the function will be inside the objects methods the structure  (name of the objects,set of properties or one,set of funtion or one),literal notation is the easiest and most popular way to create objects , in javascript objects we can access the fucntion using dot notation and we can accessing the properties using square brackets , the DOM is responsible  for telling how the browser should create a model in html page and how javascript can access and update the content of the web page ,the model that DOM create it call DOMtree that are store in the browser memory,the DOMtree is consist the four node (document,html,body,div),the atribute inside the element are not child for them they are part of them , when we want to edit something in DOMtree first we locate the place of the element the access the content some methods for access element:
* get Element Byld() 
* querySelector () 
* getElementsByClassName()
* getElementsByTagName() 
* querySelectorAll() 
* parentNode
* previousSibling /nextSibling 
* firstChild / lastChild

## the DOM working with the node not with element directly,some methods to work with node and update content:
* nodeValue
* create Element() 
* createTextNode() 
* appendChild() / removeChild() 
* hasAttribute() 
* getAttribute() 
* setAttribute() 
* removeAttribute() 

## Nodelists(live Nodelist,static Nodelist) look like arrays and are numbered like arrays, but they are not actually arrays; they are a type of object called a collection.

### the method that are find elements in the dom tree are called DOM queries,we need store elements in variables becuase we can use them more than once , some time queries return one element some time return more than one  , we can access the elements by thier id,we can select one element from node list  and we can access the elements using class name,tag name, css selector , we use loop inside the nodelist to chose elements, we can change select the element for example from parent to child  and we can edit the node or next node or the previous and we can delete the content or adding element delete
