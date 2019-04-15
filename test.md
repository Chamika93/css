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

## **Background**

The background-size property sets the size of the background image.
```
background-size: auto|length|cover|contain|initial|inherit;
```
https://css-tricks.com/almanac/properties/b/background-size/

https://www.w3schools.com/cssref/css3_pr_background-size.asp

this sets linear-gradient towards bottom right corner
```
background-image: linear-gradient(to right bottom,#7ed56fcb,#28b485b2),url(../img/hero.jpg); 
```

The background-position property sets the starting position of a background image.
```
background-position: value;
```
https://www.w3schools.com/cssref/pr_background-position.asp

https://css-tricks.com/almanac/properties/b/background-position/


