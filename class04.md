# Readings : HTML Links, JS Functions, and Intro to CSS Layout


## i understand the concept of link it us use to link pages together or website , there is more than one type for links one that let you move to other website(absolute URL) , one that let you move to other page inside the website (relative URL),one let you move to other part of the page ,one it open in other window of the browser , one start your email program the links can be written in `<a>` element inside the html.


## the structure of the link :
* open tag
* close tag
* title of link
* href:its the place that the link should send you to it  and we put the link inside it 

### first thing we build in the website is home page the extention will be index.html  and the relationship between the folders ,files is like family tree ,as i read for every image in the website it has own url to show on the website,we use relative URLs it use to conect the webpages of the same site it is shorthand  to tell the browser where to find files

### the type of relative link :
* same Folder :`<a href="reviews.html"></a>`
* Child Folder:`<a href="music/listings.html"></a>`
* Grandchild Folder:`<a href="movies/dvd/reviews.html"></a>`
* Parent Folder:`<a href="../index.html">Home</a>`
* GrandParent Folder:`<a href="../../index.html">Home</a>`


### there is attribute  call mailto we put it inside the href  to creat start up email programe ,if we want to open the link in new window we use the target attribute then we put inside it (_blank) attribute, if we want to go to the part of the page through the link we should give the section or the div or any element id then we put   hashtag inside the href then we put the name of id , and if we want to move to part that is in other page we should right the url of the page then hashtag then the name of the id of this part

### the layout is the concept of how the page will look like in the browser what is the postion of the element and how the are structure and how will the page look like in different pages, some element the css treat them as block level box and some of them treat them as inline elements because the css consider each element as box

 ### if the any element has inside it any other element it will call the contain element,the css has alot of properties that can control the postion of the elements and the layout of the page there is types of  positioning schemes (Normal flow,Relative Positioning,Absolute positioning),to determine where is box postion through boxoffset properties there is ( Fixed Positioning ,Floating Elements),to control which box have the priority to appear we use z-index

#### there is frame works to help u in the layout,some web developer try to make more than one file css one file for layout one for font ,the css benefit we make the webpage is responsive to all devices

# i understand the concept of function it is consist statements that are grouped together to preform task the method is the same of the function but is created inside the objects and we can recall the function whenever we want to do the same task.

## the function contain the keyworld and name of it and parameter and the return value :function name(parameter){return value;}

### when the function need information we put inside it parameter,some function return on value and other function return more than one value it depend of the task


#### we can call the function throug put the fucntion name just like this : functionname();

#### there is two type of variables (local,global).

### i understand the concept of pair programming it contain  two developers one of them are responsible for all the activites on the computer ( handling the mechanics of coding, the Driver manages the text editor, switching files, version control,  writing code),the other one work as navigator(think what come next,look for error,thinking in algorthims),we use pair programming  because it is very useful when we want to build our project such as save time and  reduse the error in this way we write the code in great efficiency, pair programming is Increase cooperation  in this way the persentage of the error will be low , learing from each other becuase everyone of them have specific skills,It is based on increasing the skill of communication because it needs to always speak with the other party in the project clearly, thus increasing your skills in speaking and communicating ideas, also based on training you to prepare on the work environment because most of them consist of more than one person, not one person