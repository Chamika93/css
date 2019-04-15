# **CSS CHEAT SHEET**

## **Universal styles**

These style going apply to every element in the html
```
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```
## **Adding Fonts**

Importing from google fonts->this is in the head section of html page
 ```
 <link href="https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900" rel="stylesheet">
 ```
adding fonts to the body so it will inherit to all the other elements inside body
*some parameters like padding is not going to inherit*

```
body{
      font-family: "Lato",sans-serif;
      font-weight: 400;
      font-size: 16px;
  }
 ```
 ## **Size , Height , width**
 
By default, the width and height of an element is calculated like this:

width + padding + border = actual width of an element
height + padding + border = actual height of an element

box-sizing:property allows us to include the padding and border in an element's total width and height.
```
 box-sizing: border-box;
```

height: vh means the percentage of viewport hieght ex: 95vh means 95% view port height



background-size: cover; this will fi the element in the viewport
background-image: linear-gradient(to right bottom,#7ed56fcb,#28b485b2),url(../img/hero.jpg); This set the gradient to bottom right corner

padding is not get inherited
