# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow



# i understand the concept of list it is html element that we use when we have more than item that are related together and we want to display it on page there are three types of list:
* ordered list: `<ol>`that mean each item of list is numbered
* unordered list :`<ul>`that mean each item of list is not numbered
* definition list :`<dl>`we use this list when we have terms that we want to put explain for them 
## explain some tags:
* `<li>`:each item of list will be inside this tag
* `<dt>`:this element contain the terms that we want to explain
* `<dd>`:this elemen contain the the explanation
## there is option that we can have list inide list that is what we called nested list 


## the css consider the html element is surrounded by box and css add properties to this box and the element the css can control the height and width of the box

## some properties in css :
* height
* width
* max / min - height
* max/ min - width
* overflow : this property is responsible for display the content if the contet are bigger than container through (hidden or scroll)

### every box in the html has three properties (border,margin,padding) that can be edit as we want , we can change the border width , style and color , margin is responsible for spaces between the content but padding is responsible for spaces between the content and the border.

### the properties that are responsible about distance are values be in pixels or percentage or ems. we can use distance for the all direction , there is property that we can make the boxes is center or the text that is inside the boxes (`text-align`)

### the property display is responsible for how to display content there is for type (inline,block,inline-block-none)

### the property visibility(visibile,hidden) give us option to hide the conten or the box but there place still reserved for them.

#### there is property that allows to make shadow to the box there is four attribute of it (Horizontal offset,Vertical offset,Blur distance,Spread of shadow) 

### border raduis allows to change the shpae of the box and edit the edges

## javascript note : 
### array is variable that can store many values that are related to each other array is very useful if we want to store list itmes but we donot know my much will the list contain we can create array just as any variable give it name but there is two ways to creat array (array literal,array constructor)  , the values in array can be accessing and change , the list numbering start from zero in array

#### if else statement are use if there is any decision should be made if the decision come with result true the code inside the (if) but if the result come false the code inside the (else ) , the if else statement  is very useful becuase it is provides two option that the code the can take path one them 

### there is other conditional statement it is called the switch contain the value of the variable and the some cases that see if the value of variable is equal to one of the cases

### type coercion that means javascript change the data type of the variable  behind the scene that may appaer some unexpected result in the code because there is no determine of the data type in java script this call  weak typing  , however in other languages  you should determine the type of variable this is called strong typing

## there is two types of values truthy and falsy

#### the logical values return the value that they stopped in it and they processed from the left to right 

#### loop it depends on the result of the condtion if it return ture the block inside the loop will start proccess and will not stop until the condtion return false value there is there types of loop (for ,while,do while), we ue for loop when we know how many times need to be repeated but the while loop we use when we donot know how many times need to repeate , the difference between do while and while is the do while is running the code once even condition is met 

#### the structure of the for is :
* the key world
* condition
* carly brackets
#### the condition is combine three statement:
* initialization var i =1;
* condition i<10
* update i++

**break key world is telling the loop to stop  interpret and go to the next statement outside the block**

**continue  key world tell the  interpret to keep going with current iteration**
