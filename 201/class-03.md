## Html list: 

### ther are 4 type of list we use it : 
1. ordered list : its give you list with a numer 1- 2- 3-   
we use :  
```
<ol>
  <li>
  </li>
  <li>
  </li>
<ol>
```
this code will give you liste like this:  
1.  
2.  

2. unordered list : give you list with a dote .   
we use:  
```
<ul>
  <li>
  </li> 
  <li>
  </li> 
</ul>
```
this code will give you list like this  
*  
*  

3. Definition list : consists of a series of terms and their definitions .  
we use:   
``` 
<di>
  <dt>
  </dt>
  <dd>
  </dd>
</di>
``` 
4. Nested list : its list inside list  
```
<ul>
  <li>1</li>
  <li>2
    <ul>
      <li>1</li>
      <li>2</li>
      <li>3</li>
    </ul>
  </li>
  <li>3</li>
</ul>
```

## Box :  
its a code that we write it on css to make a Framework , thare are some e.g:  


to make box with dimintion height & width  :   
```
div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
```

to make bok with limiting width or hight : 
```
td.description {
min-width: 450px;
max-width: 650px
}
``` 
```
td.description {
min-hight: 450px;
max-hight: 650px
}
``` 
Overflowing Content : tells the browser what to do if the content contained within a box is larger than the box itself  

``` 
p.one {
overflow: hidden;}
p.two {
overflow: scroll;}
``` 
border width : to make dimintion for the box  
```
p.one {
border-width: 2px;}
p.two {
border-width: thick;}
p.three {
border-width: 1px 4px 12px 4px;}
```
border style : change the style for the box  
```
p.one {border-style: solid;}
p.two {border-style: dotted;}
p.three {border-style: dashed;}
p.four {border-style: double;}
p.five {border-style: groove;}
p.six {border-style: ridge;}
p.seven {border-style: inset;}
p.eight {border-style: outset;}
```
border coler : coloring the box  
```
p.one {
border-color: #0088dd;}
p.two {
border-color: #bbbbaa #111111 #ee3e80 #0088dd;}
```

## switch statment in javascrebt : 
we use switch statmen if we have alot of case with one var - faster than the if statment-  

```
var msg; 
var level = 2; 

switch (level) { 
case 1: 
     msg = 'Good luck on the first test ' ; 
     break; 

case 2: 
     msg = 'Second of three - keep going!'; 
     break;

case 3: 
     msg = ' Final round, al most there!'; 
     break;

default : 
     msg = 'Good l uck!'; 
     break; 
} 
``` 
